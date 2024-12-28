# Air Quality Classification Project 🌍
This project is a machine learning-based air quality classification model that predicts air quality levels using supervised learning techniques.
---
## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Target Variable](#target-variable)
- [Approach](#approach)
- [Results](#results)
- [How to Run the Project](#how-to-run-the-project)


- ## Overview
This project implements a machine learning pipeline to classify air quality into categories. It includes preprocessing, feature engineering, hyperparameter tuning using GridSearchCV, and evaluation using metrics like accuracy, classification reports, and ROC curves.
## Dataset
Temperature (°C): Average temperature of the region.
Humidity (%): Relative humidity recorded in the region.
PM2.5 Concentration (µg/m³): Fine particulate matter levels.
PM10 Concentration (µg/m³): Coarse particulate matter levels.
NO2 Concentration (ppb): Nitrogen dioxide levels.
SO2 Concentration (ppb): Sulfur dioxide levels.
CO Concentration (ppm): Carbon monoxide levels.
Proximity to Industrial Areas (km): Distance to the nearest industrial zone.
Population Density (people/km²): Number of people per square kilometer in the region.

## Target Variable: Air Quality Levels
     * Good: Clean air with low pollution levels.*
     * Moderate: Acceptable air quality but with some pollutants present.
     * Poor: Noticeable pollution that may cause health issues for sensitive groups.
     * Hazardous: Highly polluted air posing serious health risks to the population.

## Approach
To tackle the problem of Air quality prediction, I employed a systematic machine learning workflow comprising several key tasks:

## 1. Data Exploration
* Investigate the dataset to understand its structure, identify data types, and uncover initial insights.
* Visualize distributions, relationships, and trends within the data using graphs and statistical measures.

## 2. Data Cleaning
* Handle missing values through imputation or removal based on their significance and impact.
* Detect and correct inconsistencies or anomalies within the dataset to ensure data integrity.

## 3. Feature Engineering
* Create new features that could enhance model performance, such as aggregating variables or encoding categorical variables.
* Select relevant features that contribute significantly to predicting air quality while eliminating redundant or irrelevant ones.

## 4. Model Building
* Experiment with various classical machine learning algorithms to determine which models best fit the data. Potential algorithms to consider include:
     * Logistic Regression: A statistical model suitable for binary classification.
     * Decision Trees: A non-linear model that makes decisions based on feature values.
     * Random Forest: An ensemble method that utilizes multiple decision trees to improve accuracy and robustness.
     * Hyper parameter tunning with Random Forest( Which is best suits for this prject).
     * Gradient Boosting Machines (GBM): A powerful ensemble technique that builds models in a stage-wise manner to optimize        prediction accuracy.
     * Support Vector Machines(SVM): A model that identifies the hyperplane that best separates classes in the feature space.

## 5. Model Testing
* Evaluate the performance of the models using appropriate metrics such as accuracy, precision, recall, F1-score, and area 
  under the ROC curve (AUC-ROC).
* Utilize cross-validation techniques to ensure the models generalize well to unseen data.


## Results
- Best model: Random Forest Classifier tunned model
- Accuracy: 96.6%
- ROC-AUC: Class 0 (1.00), Class 1 (0.96), Class 2 (1.00), Class 3 (0.99)

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Air-Quality-Classification.git
   cd Air-Quality-Classification

