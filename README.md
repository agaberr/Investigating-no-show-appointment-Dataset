# Investigating-no-show-appointment-Dataset


Overview
----
The purpose of this project is to examine a dataset containing appointment records from public hospitals in Brazil, which includes patient attributes and whether they attended their appointments. The focus of the analysis is to identify patterns that influence patients to attend or miss their scheduled appointments. The objective is to use descriptive statistics to determine which factors are significant for predicting whether a patient will attend their appointment. However, predictive analytics is not within the scope of this project.


The original problem description and data set can be found here: https://www.kaggle.com/joniarroba/noshowappointments/home

Details
----
I have examined the dataset and addressed some issues, such as standardizing names, removing incorrect data, and creating new features based on existing data. I have also analyzed most of the independent variables in the dataset and made comparisons between them and the dependent variable (no_show). However, as this was purely an exploratory analysis, there may be other possible correlations that have not been identified.

Findings
----
The most important findings are:

* 80% of patients showed up, while 20% didn't show up.
* Number of women in the dataset are greater than that of men.
* Women are more likely to attend appointments than men.
* There is no relation between people with diseases (Hypertension and Diabetes) and showing up.
* The is no relation between people who drink alcohol and showing up.
* The more patients wait for their appointments, the less likely to attend.
* The location of the hospital has nothing to do with showing up.
* Recieving an sms message with the appointment won't affect showing up.

Statistical Analysis Scope
----
Data Wrangling
Exploratory Data Analysis (EDA)
Data visualizations

Tools
----
Python, libraries: numpy, pandas, matplotlib
Jupyter Lab

