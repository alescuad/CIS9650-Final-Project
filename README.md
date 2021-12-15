# CIS9650 - Final Project

Team members:
* Sabah Javaid
* Anna Kobaivanov
* Han Sung Kim
* Kevin Linitz
* Alessandro Cuadros

Professor: Jason Tseng

Class: CIS 9650 - Fall Term 2021

# Overview

According to the World Health Organization (WHO), cardiovascular diseases are the leading cause of death globally. The team has designed this project to clean a dataset, store the data to a database object, and perform statistical analyses in hopes of finding correlations, connections, and conclusions about this condition. 

# Data Source

The dataset can be found here: https://www.kaggle.com/sulianova/cardiovascular-disease-dataset

# Data Description

The dataset features:
* Objective data: factual information
* Examination data: results of medical examinations
* Subjective data: information provided by the patient

# Database Export Information
## Database Dictionary
### Table: cardio_data

Column | Data Type | Description
--- | --- | --- 
index | integer | Unique identifier for patient record. 
age | floating | Patient's age (in years). 
gender | character (10) | Patient's gender. 
height | integer | Patient's height (in centimeters).
weight | integer | Patient's weight (in kilograms). 
systolic_BP | integer | Patient's systolic blood pressure.
diastolic_BP | integer | Patient's diastolic blood pressure. 
cholesterol | character (15) | Patient's cholesterol level summary. 
gluc | character (15) | Patient's glucose level summary. 
smoke | integer | Patient's smoke flag (0 = non-smoker, 1 = smoker). 
Alcohol | integer |  Patient's alcohol intake flag (0 = no alcohol, 1 = some or abnormal alcohol alcohol intake).
physical_activity | integer | Patient's physical activity flag (0 = sedentary, 1 = active). 
cardio_disease | integer | Patient's cardiovascular disease flag ( 0 = no cardiovascular disease, 1 = cardiovascular disease present).
BMI | floating | Patient's BMI (Body Mass Index). 
chol_High | integer | Patient's high cholesterol flag (0 = not high, 1 = high). 
chol_Normal | integer | Patient's normal cholesterol flag (0 = not normal, 1 = normal).  
blood_pressure | character (20) | Patient's blood pressure summary. 
BMI_result | character (20) | Patient's BMI level.
