# Medical Appointments No-Shows

## Overview
The goal of this project is to investigate a dataset of appoinment records for Brazil public hospitals. The data includes some attributes of patients and state if the patients showed up to appointments. The analysis should be focused on finding trends influencing patients to show or not show up to appointments. Using **descriptive statistics** the following question should be answered: What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment? Predictive analytics is out of scope of this project.

The original problem description and data set can be found [here](https://www.kaggle.com/joniarroba/noshowappointments/home)

This project was completed as part of Udacity's [Data Analyst Nanodegree](https://eu.udacity.com/course/data-analyst-nanodegree--nd002) certification.

## Details
I have looked into the dataset and managed a few problems like unifying names, removing incorrect data, adding new features based on existing data. I have also investigated most of independent variables in the dataset and made a few observations comparing them to each other as well as to the dependent one (no_show). As this was only an exploratory analysis, many potential correlations may remain uncovered. The data should be investigated further with more advanced statistical analysis to potentially reveal new insights and correlations.

For details see analysis documentation [Jupyter Notebook](https://github.com/kuang287/DataAnalyst/blob/main/Project2_Investigate%20a%20Dataset/Investigate_a_Dataset.ipynb) or [HTML](https://github.com/kuang287/DataAnalyst/blob/main/Project2_Investigate%20a%20Dataset/Investigate_a_Dataset.html).

## Findings
The most important findings are:
- It is more likely that patients will show up to their appointment on same day, and less likely to show up as the awaiting time is getting longer.
- There are patients made multiple appointments. The patients made appointments in high frequency will be more likely to show up than average.
- It is more likely that patients who received SMS message will not show up compared to the ones not received.
- For each gender or in total, the highest no-show rate is under age 10's, and it goes down as age increases.
- There is not much difference on the no-show rate between different gender.
- Patients with disease are more likely to be middle-aged (50's-70's), while the peak of patients with alcoholism will be younger at around 50's than patients with hypertension or diabetes which is around 60's.
- Patients with hypertension or diabetes are more likely to be female, with the proportion more than twice as male. For patients with alcoholism, it is more likely to be male with the proportion nearly twice as female.

## Statistical Analysis Scope
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Data visualizations

## Tools
- Python, libraries: pandas, matplotlib, seaborn
