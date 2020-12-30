# Heart_Disease_Classifier

Heart disease is a class of diseases that involve the heart or blood vessels. Cardiovascular diseases are the leading cause of death globally. This is true in all areas of the world except few. Deaths, at a given age, from CVD are more common and have been increasing in much of the developing world, while rates have declined in most of the developed world since the 1970s.

## About the Dataset

This database contains 76 attributes, but all published experiments refer to using a subset of 13 of them.The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 which means presence of no hear disease and 1 means presence of disease. Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence i.e value 1 from absence (value 0).

The data includes 303 patient level features including if they have heart disease at the end or not. Features are like;
Age: Obvious one.
1. Sex:
  * 0: Female
  * 1: Male
2. Chest Pain Type:
  * 0: Typical Angina
  * 1: Atypical Angina
  * 2: Non-Anginal Pain
  * 3: Asymptomatic
3. Resting Blood Pressure: Person's resting blood pressure.
4. Cholesterol: Serum Cholesterol in mg/dl
5. Fasting Blood Sugar:
  * 0:Less Than 120mg/ml
  * 1: Greater Than 120mg/ml
6. Resting Electrocardiographic Measurement:
  * 0: Normal
  * 1: ST-T Wave Abnormality
  * 2: Left Ventricular Hypertrophy
7. Max Heart Rate Achieved: Maximum Heart Rate Achieved
8. Exercise Induced Angina:
  * 1: Yes
  * 0: No
9. ST Depression: ST depression induced by exercise relative to rest.
10. Slope: Slope of the peak exercise ST segment:
  * 0: Upsloping
  * 1: Flat
  * 2: Downsloping
11. Thalassemia: A blood disorder called 'Thalassemia':
  * 0: Normal
  * 1: Fixed Defect
  * 2: Reversable Defect
12. Number of Major Vessels: Number of major vessels colored by fluoroscopy.

## Working on the Notebook

### Feature Engineering
Feature Engineering is used to Prepare the input dataset which is compatible with the machine learning algorithm requirements and also help to Improve the performance of machine learning models. In this notebook I have used Imputation, One-Hot-Encoding, Scaling as a part of feature Engineering.

### Exploratory Data Analysis
EDA is a way of visualizing, summarizing and interpreting the information that is hidden in rows and column format. In this notebook I have used EDA for visualizing and interpreting the different features and their relation with each other. 

### Data Visualization
Data visualization is the practice of translating information into a visual context, such as a map or graph, to make data easier to understand and pull insights from. The main goal of data visualization is to make it easier to identify patterns, trends and outliers in large data sets. In this notebook I have used Matplotlib, Seaborn and Plotly for various visualization patterns. 

### Predictive Algorithms
Predictive analytics is the use of data, statistical algorithms and machine learning techniques to identify the likelihood of future outcomes based on historical data. In this notebook I have used Decision trees and Random Forest to predict future outcome. 


