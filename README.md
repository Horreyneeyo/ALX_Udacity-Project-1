# Brazil Medical Appointments Dataset Analysis

## Introduction
This project deals with the data analysis of No-Show medical appointments in Brazil. This dataset collects information
from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patients are included in each row. 

Some of the features such as Gender, Age, Neighbourhood, Scholarship, Hipertension, Diabetes, Alcoholism, Handcap, SMS_received are the factors and variables that can be used to illustrate if a patient would show up for their scheduled appointment. 

The predicted variable with is the 'No-show' indicates whether the patient dis not show up for the appointment in terms of 'Yes' or 'No'.

Hence the study in this section imports the dataset itself and downloads packages that are necessary for exploring the dataset analytically and illustratively

## Research Question
This data analysis project seeks to understand important factors that could influence the prediction of a patient attending their scheduled medical appointment in Brazil. Furthermore, it is hoped that the statistical results from this analysis would provide necessary information for the modification of brazilian medical practices and policies especially in the areas covered in the dataset. 

## Conclusions

### Results
It can be observed generally that 0.3% more females would not show up for medical appointments than male. however, this may not be entirelt true, as the dataset is imbalance and contains far more female IDs than males IDs. In fact most of the males are between the ages of 0-18(children) while the females are mostly adults (30-60). 
 
>On a probability basis, the male youths are far more likely not to show up for appointment even with the less number of appointments than any other age-categories while the female adults are more likely to show up for medical appointment in brazil

>it can be seen that apart from ILHAS OCEÃ‚NICAS DE TRINDADE and PARQUE INDUSTRIAL locations, the relative probability of patients from the other 79 locational note turning up is about 20%. if you are from ILHAS OCEÃ‚NICAS DE TRINDA, you are most likely not to turn up. if you are from PARQUE INDUSTRIAL, you are more likely to turn up

>More patients are appointed to come for medical exercise mostly in May 2016 than in April or less likely in June. Asides this it can be seen that the time of appointment doe not greatly contribute to patients not showing up. However, there is need for more information on the time length of appointment booking, so that 'scheduledDay' as given can be used determine if it is a factor in predicting if the patient would show up

>Also, SMS recieved has an impact on both gender showing up for the appointment particularly the males. The rest of the feature do not have an appreciable impact or factor in imfluence whether patients would turn up for medical appointments or not

### LIMITATIONS 
More information is required to be provided as regards the 'ScheduledDay' which would inform the timeline a booking is done to the day of apppointment. Hence, 'ScheduledDay' details can be deployed and wrangled in understanding if this a factor for patients showing up for medical appointment. Also, more data should be supplied for a standard/longer period of time range. So that the insights culled from the data analysis can be more accurate. As the information we have as regards the timelines (AppointmentDay and scheduleDay) are skewed  
