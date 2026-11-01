# Sleep Health and Lifestyle Prediction 

## Project Overview
In this project, we analyze the "Sleep Health and Lifestyle Dataset" to explore the relationship between daily habits (such as physical activity, stress levels, and BMI) and overall sleep quality. The primary goal is to identify key factors that affect sleep and build a Machine Learning model to predict the presence of sleep disorders (Insomnia, Sleep Apnea, or Healthy).

## Data Cleaning & Preprocessing
* Handled missing values (filled NaN in 'Sleep Disorder' with 'Healthy').
* Standardized BMI categories for consistency.
* Split the 'Blood Pressure' column into separate 'Systolic' and 'Diastolic' numerical columns.

## Exploratory Data Analysis (EDA)
Conducted visual analysis using Seaborn and Matplotlib to examine how various lifestyle factors and stress levels impact sleep duration and quality. 

## Machine Learning Model
* **Algorithm:** Random Forest Classifier
* **Performance:** Achieved **88% accuracy** in predicting sleep disorders based on lifestyle and health metrics.
* **Libraries Used:** Python, Pandas, Matplotlib, Seaborn, Scikit-Learn.
