

# 2018 BRFSS Survey Data Analysis
## Utilizing Machine Learning Classifier Algorithms to Classify 2018 BRFSS Survey Data Prepared by the CDC

## Required Libraries
* pandas
* scikit-learn
* numpy
## Files Included:
- `data` folder: Contains source data and processed data.
- `images` folder: Charts and graphs used for project presentation.
- `dataPrep`: Documentation of the data cleaning process performed.
- `data_processing`: Details on attribute selection methods, model creation, and model evaluation.
- `project_report`: A summary report of the project.

## Project Objective 
The goal of this project is to build and evaluate classifier models using real-world data. This involves building 25 classifier models, utilizing various attribute selection methods. The models will be assessed based on a weighted average of TP rate, FP rate, precision, recall, and F-measure.

## Project Outcome
- Successfully built and tested 25 classifier models using real-world data.
- Achieved an average accuracy score of 70% and a sensitivity rate above 50%.
- Employed data cleaning, preprocessing, feature engineering, and model selection techniques.
- Utilized Python, pandas, scikit-learn, seaborn, and other tools to optimize model performance and understand feature importance.

## Project Steps
1. **Data Cleaning**: 
   - Extensive data cleaning was required due to the real-world nature of the dataset.
   - Addressed issues such as populating missing values and replacing outliers with mean, median, or most frequent values.
   - Adjusted data types for analysis compatibility.

2. **Data Processing and Model Creation**: 
   - Executed five iterations, each employing different attribute selection methods and classifier models.
   - Evaluated models based on accuracy, error rate, sensitivity/recall, and precision rate.

3. **Best Model Selection**: 
   - Selected the best model based on average performance metrics and the efficacy of the feature selection method.
