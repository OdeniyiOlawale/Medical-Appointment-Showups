# Medical-Appointment-Showups
## Introduction 
## - Problem Statement
Hospitals need to understand the pattern with which their patients show up for their treatment on the appointment days. Patients who register for medical appointments sometimes do not make it to the hospital on their appointment days. This project analysis is descriptive in nature, and it's one of the primary requirements for completing my Data Analytics Nano Degree with ALX-T Udacity. I choose to work on this project because there is tendency that a patient's condition worsens as a result of his/her failure to appear on their appointment day. In order to make the most of this project, I am expected to collect the medical data from a source, ask questions about it, explore the data to answer these questions, identify patterns and insights and give recommendations or predictions. 
## Project Objectives
This project was guided by the following research questions:

1. Which patients' age group have the best show up on their appointment day?
2. What variables are closely associated with the age group that has the highest attendance?
3. What factors are important in predicting whether a patient will show up for their treatment?

## Data Sourcing 

The data for this study was initially collected by a hospital in Brazil and made available for public use on [kaggle](https://kaggle.com) The data was collected from patients who lived across 83 regions in the country. The dataset was simply downloaded from this [kaggle](https://kaggle.com) page.

## Methodology
### Python Libraries
The libraries used on this project include:

* Pandas – For storing and manipulating structured data. Pandas functionality is built on NumPy
* Numpy – For multi-dimensional array, matrix data structures and, performing mathematical operations
* Matplotlib - For creating static, animated, and interactive visualizations in Python
* Seaborn - For exploring and understanding the data 

The Analytical Process is as follows:
> The Data was first cleaned to ensure it's of the right quality, and structure suitable for the analysis. 
>
> The data was then explored to spot relationships and behaviours of variables. Several features were also extracted from existing variables at this stage
>
> Basic statistical summaries were carried out to manipulate variables and features
>
> Visualisation of Results

## Conclusions and Recommendations

It was discovered that the 'adults' generally honour their appointments better than any of the other age groups. Further investigation was carried out to suggest factors responsible for this and it was discovered that alcoholic adult patients show up better on their appointment days. 

The 'wait_time' was found to be most associated with whether a patient will show up or not. Also, patients who did not have any chronic disease (hypertension and diabetes) also appeared to show up better on their appointment days. These two variables according to the analysis in this report should be considered as important factors that can be used to predict if a patient will show up or not.

