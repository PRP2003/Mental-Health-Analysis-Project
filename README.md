# Mental-Health-Analysis-Project

## Project Overview
This project focuses on developing machine learning models to predict depression using various personal and environmental factors. The analysis involves comprehensive data preprocessing, feature engineering, and model training to understand and predict mental health outcomes.

## Dataset
The project uses a dataset containing information about individuals' mental health, including:
- Demographics (Age, Gender, City)
- Professional Status
- Academic and Work Pressures
- Sleep Duration
- Dietary Habits
- Suicidal Thoughts
- Family History of Mental Illness
- Dataset for this project is obtained from Kaggle Competition Titled : Exploring Mental Health Data (Playground Series - Season 4, Episode 11)
- Link for Dataset : https://www.kaggle.com/competitions/playground-series-s4e11/data 

## Project Structure

### Key Components
- Data Cleaning and Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Machine Learning Model Training
- Model Evaluation

### Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- LightGBM
- XGBoost

## Preprocessing Techniques
- Handling Missing Values
- Label Encoding
- Target Encoding
- Standard Scaling
- Feature Selection

## Machine Learning Models
The project implements multiple classification models:
1. Logistic Regression
2. Support Vector Machines (SVM)
   - Standard SVM
   - Linear Kernel SVM
3. LightGBM Classifier
4. XGBoost Classifier

## Key Preprocessing Steps
- Standardized numerical features
- Encoded categorical variables
- Handled missing values with imputation
- Created correlation matrix for feature analysis

## Model Performance
Multiple models were trained and evaluated:
- Logistic Regression
- SVM (Standard and Linear Kernel)
- LightGBM
- XGBoost

## Visualization
The project includes a correlation matrix heatmap to understand feature relationships.

## Installation

1. Install required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Future Improvements
- Hyperparameter tuning
- Advanced feature engineering
- Ensemble methods
- More sophisticated imputation techniques

## Model Valuation 
With the above machine learning model, on evaluating with test dataset obtains an accuracy score of 92.382%  

