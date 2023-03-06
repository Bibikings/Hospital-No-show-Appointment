# Hospital-No-show-Appointment

> The no show appointments dataset was adopted for this project, the dataset contains information from 100k medical appointments in Brazilto. 

>I'll be analysing to determine whether or not patients show up for their appointments, the characteristics of patients that do show up and how they differ from those that don't.

## Column names
#### PatientId - an ID unique to each patient AppointmentID - appointment ID assigned to each patient for the appointment session _The appoinment and patient ID are not very significant for this analysis

>Gender - gender ScheduledDay - this signifies the day the appointment was scheduled AppointmentDay - date of appointment Age - age of the patient Neighbourhood - neighbourhood where the patient lives 
Scholarship - whether patient is enrolled in the Brazillian welfare program Hipertension, Diabetes, Alcoholism, 
Handcap - these three columns are medical condition(s) of a patient SMS_received- notification of appointment details to patient
No-show - whether patient showed up for his/her appointment

## Question(s) for Analysis

>Age distribution of patients

>What gender is likely to show for an appointment?

>Does medical condition play a role in patients keeping to appointments?

>Does recieving sms matter?

### Libraries for this project
>import pandas as pd

>import numpy as np

>import matplotlib.pyplot as plt

>%matplotlib inline

>import seaborn as sns

### Data Wrangling

>After loading in the dataset, I used different functions to understand the dataset better and determine the cleaning it needed. The dataset was fairly certain and little cleaning was done which were
>renaming the incorrect columns, changing data types, dropping insignificant columns

## Conclusion
Findings: Analysis was done on the No-show appointments dataset; the No-show column was a constant variable compared to other variables(columns) in the dataset. Observations:

> There are two sets of patients – those that showed up for appointment and those that did not show up.

> The number of patients that showed up was greater than those that did not.

>Females are more than males.

>Been enrolled in the scholarship program(social welfare program by the Government of Brazil) does not have impact on patients keeping to appointments. More details on the welfare can be found on this link Bolsa Familia

>SMS notification does not appear to determine whether a patient showed up or not.

>Age distribution varies with an average of 37 for both sets of patients.

>Medical condition appears to have the greatest impact on patients with severity of the illness determining those that keep to appointment, Hypertensive patients have the highest number.

>There happens to be location spread among patients, however, there is no data showing the hospital location and travel duration to determine if distance impacts patients availability on appointment day.

## Limitation 

> There is no data showing the hospital location and travel duration to determine if patients location impacts patients availability on appointment day.
