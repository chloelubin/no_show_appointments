### No-show appointments

In this project, I'll explore a dataset of no-show medical appointments in Brazil. The dataset was originally 
published on Kaggle by [Joni Hoppen](https://www.kaggle.com/joniarroba) and can be found [here](https://www.kaggle.com/joniarroba/noshowappointments). The main question that this dataset raises is whether 
it is possible to predict the likelihood of no-show appointments based on determining factors (demographics, 
medical information, time, etc.). 

**I performed the following operations:**
1. Saved the dataset in a pandas dataframe
2. Cleaned the column names, removed incorrect datapoints, and changed datatypes in the data wrangling phase
3. Analyzed the following research questions in the Exploratory Data Analysis (EDA) phase:
  a. Is demographic information indicative of no-show appointments?
  b. Is the day of week a significant determinant of no-show appointments?
  c. Is the time between the scheduled and appointment day a good indicator of no-show appointments?
  d. How do medical conditions affect the likelihood of no-show appointments?
  
  
**I arrived at the following conclusions:**
* The gender variable isn't a significant factor contributing to the high number of no-show appointments by itself. 
Combined with age, we see that there is a higher no-show rate for male patients between the ages of 0 and 10 and betwen 
15 and 60 years old for female patients. We also observe that older patients of both genders seem more reliable to show 
up to their appointment.
* Timing also matters a lot in the likelihood of observing a no-show. There is a higher number of no-shows on Tuesdays 
and Wednesdays. In addition, patients who scheduled their appointment far in advance seemed to have a lower number of 
no-show appointments than those who scheduled theirs within a shorter timeframe.
* Finally, medical conditions are determining factors that can be used to estimate the probability of a no-show. As we 
notice from our analysis above, two medical conditions in particular seem to affect the no-show rate: hypertension and 
having a single handicap.
