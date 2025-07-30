# Sleep Disorder Prediction Project

## Project Overview

The purpose of this project is to analyze factors that affect sleep health and predict which sleep disorder a person may have based on various factors such as Sleep Quality, Stress Level, BMI Index, Blood Pressure, etc. The dataset used for this project was sourced from Kaggle. The project involved data preprocessing to fill null values, exploratory data analysis (EDA), and the implementation of machine learning models to make predictions.

## Key Observations from EDA

- Individuals aged over 43 years are more likely to experience sleep disorders.
- On average, females tend to have better sleep quality compared to males.
- Engineers generally have better sleep quality, while Sales Representatives have poorer sleep quality.
- Higher stress levels are associated with an increased likelihood of sleep disorders.
- Individuals with sleep disorders have lower sleep quality ratings compared to those without disorders.
- People in the Obese and Overweight BMI categories tend to experience more sleep disorders.
- Individuals who sleep more than 7 hours have a significantly lower chance of having a sleep disorder.

## Methodology

### Data Splitting

The dataset was split into training and testing sets in a 3:1 ratio.

### Models Used

Three machine learning models were used:
1. Logistic Classification
2. K-Nearest Neighbors (KNN) Classifier
3. Random Forest Classifier

The same training and testing sets were used for all models. 

### Model Performance

- **Random Forest Classifier**: Best performing model with an accuracy of 89%.
  - Accuracy: 89%
  - Recall: 89%
  - Precision: 90%
  - F1-Score: 89%
- **KNN Classifier**: Performed well but not as good as Random Forest.
- **Logistic Classification**: Achieved 86% accuracy, which was the lowest among the three models.

## Important Features

Based on the Random Forest Classifier, the top three important features for detecting sleep disorders are:
1. Blood Pressure
2. BMI Category
3. Age

## Conclusion

The Random Forest Classifier was identified as the best model for predicting sleep disorders in the given dataset, achieving an accuracy of 89%. The top three contributing features to the prediction are Blood Pressure, BMI Category, and Age.

## Dataset

The dataset for this project was obtained from [Kaggle](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/data).

## Author

This project was completed by Hrithik Manda.

## Acknowledgments

Special thanks to Kaggle for providing the dataset used in this project.
