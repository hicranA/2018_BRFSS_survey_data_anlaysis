# 2018_BRFSS_survey_data_anlaysis
using machine learning classifier algorithms to classify 2018 BRFSS Survey Data prepared by CDC


## Required Libraries
* pandas
* scikit-learn
* numpy

## Files Included:
data folder: source data and processed data
images folder: charts and graphs that used for project presentation
dataPrep: data cleaning process performed
data processing: attribute selections methods, model creation, and model evaluation
project report: project summary report 

## Project Objective 
The goal of this project is to build and test classifier models using a real-world data by building 25 classifier models by using classification models multiple times using different attribute selection methods.The models will be evaluated on weighted average of  TP rate, FP rate, precision, recall, F-measure

## Project Outcome: 
Built and tested 25 classifier models using real-world data, achieving an average accuracy score of 70% and sensitivity rate above 50%. Employed data cleaning, preprocessing, feature engineering, and model selection techniques using Python, pandas, scikit-learn, seaborn, and other tools to optimize model performance and gain key insights into feature importance

## Project Steps
1. Data cleaning: Data cleaning process took really long for this project because it is a real world data. Some of the issues that I worked on populating missing values and replacing outliers  with mean, median , and most frequent, adjusting data types 
2. Data Processing and Model Creation: In this steps I have created five iterations and each iterations I have used different attribute selection method and  classifier model. At the end of this step we evaluate our models based on accuracy,error_rate,sensitivity_recall, precision_rate
3. Best Model Selection: Based on the average evaluation matrics we select the best model with best feature selection method. 

## Updated at:
12/20222