# housing-price-prediction-using-machine-learning
MSc dissertation project exploring UK housing price prediction using machine learning algorithms.

# A Data-Driven Approach to Housing Price Prediction Using Machine Learning Algorithms

## 1. Project Overview

Housing prices are influenced by several factors, including property characteristics, location and market conditions. Understanding these factors and estimating property values accurately can be useful for buyers, sellers, investors and other stakeholders in the housing market.

This project explores a data-driven approach to housing price prediction using machine learning algorithms and UK housing transaction data.

The main aim is to investigate the dataset, identify relevant features, develop predictive models and compare their performance. The project also explores model interpretability techniques to better understand how different features influence predictions.

This dissertation was completed as part of the MSc Data Science and its Applications programme at the University of Essex.

## 2. Problem Statement

Housing prices can vary considerably depending on property characteristics and other influencing factors. Traditional approaches to estimating property values may not fully capture complex relationships between these factors.

This project investigates how machine learning techniques can be applied to historical housing transaction data to develop predictive models and understand the factors associated with property prices.

## 3. Project Objectives

The main objectives of this project were:

- Analyse UK housing transaction data to understand its structure and characteristics.
- Perform data cleaning and preprocessing to prepare the dataset for analysis.
- Conduct exploratory data analysis to identify patterns, distributions and relationships.
- Apply feature engineering techniques to prepare relevant variables for modelling.
- Develop machine learning models for housing price prediction.
- Compare the predictive performance of different algorithms.
- Evaluate model performance using appropriate regression metrics.
- Apply explainable AI techniques to interpret model predictions and feature contributions.

## 4. Dataset

The project uses UK housing transaction data as the basis for analysis and predictive modelling.

The dataset was examined to understand its structure, identify relevant variables and prepare the information for machine learning.


## 5. Technologies and Tools

The project involved the following technologies and technical areas:

- **Python:** Data analysis and machine learning implementation.
- **Pandas:** Data manipulation and preprocessing.
- **NumPy:** Numerical operations.
- **Scikit-learn:** Machine learning model development and evaluation.
- **SHAP:** Model interpretation and feature contribution analysis.
- **LIME:** Local interpretation of individual model predictions.


## 6. Methodology

The project followed a structured data science workflow.

### 6.1 Data Understanding

The initial stage involved examining the housing transaction dataset to understand its structure, available variables and suitability for predictive modelling.

### 6.2 Data Preprocessing

Data preprocessing was carried out to prepare the dataset for analysis and modelling. This stage involved examining data quality and applying appropriate preparation techniques.

### 6.3 Exploratory Data Analysis (EDA)

Exploratory data analysis was performed to investigate the characteristics of the dataset, understand variable distributions and identify relationships between housing features and transaction prices.

### 6.4 Feature Engineering

Feature engineering was used to prepare and transform relevant variables for machine learning. The aim was to provide suitable input features for the predictive models.

### 6.5 Machine Learning Model Development

Three machine learning algorithms were investigated:

**Linear Regression**

Used as a regression approach to model relationships between input features and housing prices.

**Random Forest**

Used as an ensemble learning approach to investigate predictive performance using multiple decision trees.

**Gradient Boosting**

Used as a boosting-based regression approach to develop predictions through sequential model improvement.

### 6.6 Model Evaluation

The models were evaluated using regression performance metrics to assess and compare their predictive performance.

The evaluation metrics included:

- **R-squared (R²):** Measures the proportion of variation in the target variable explained by the model.
- **Root Mean Squared Error (RMSE):** Measures prediction error while giving greater weight to larger errors.
- **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted values.

### 6.7 Explainable AI and Model Interpretation

SHAP and LIME were used to support the interpretation of machine learning predictions.

These techniques helped investigate how input features contributed to model predictions and provided additional insight into model behaviour.

## 7. Model Comparison and Results

The project investigated Linear Regression, Random Forest and Gradient Boosting.


## 8. Explainability and Interpretation

An important part of this project was exploring the interpretability of machine learning models.

SHAP and LIME were used to investigate feature contributions and understand individual predictions.

## 9. Key Learning Outcomes

Through this project, I developed practical experience in:

- Working with real-world housing transaction data.
- Data preprocessing and exploratory data analysis.
- Feature engineering for predictive modelling.
- Developing and evaluating regression models.
- Comparing different machine learning algorithms.
- Applying explainable AI techniques using SHAP and LIME.
- Communicating analytical findings through a structured data science workflow.

## 10. Repository Structure

The repository can be organised as follows. 

```text
housing-price-prediction/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── housing_price_analysis.ipynb
│
├── src/
│   └── [Python source files]
│
├── visualisations/
│   └── [Project plots and charts]
│
├── results/
│   └── [Model evaluation results]
│
├── README.md
└── requirements.txt
```

## 11. Conclusion

This project explored the application of machine learning techniques to UK housing transaction data for housing price prediction.

It involved data preprocessing, exploratory analysis, feature engineering, predictive model development, model evaluation and explainability techniques.

The project provided practical experience in applying data science and machine learning methods to a real-world prediction problem.

## 12. Future Improvements

Potential future improvements could include:

- Exploring additional relevant housing features.
- Investigating other machine learning algorithms.
- Further hyperparameter optimisation.
- Evaluating model performance on additional or more recent data.
- Improving the interpretability and presentation of model predictions.

## 13. Academic Information

**Programme:** MSc Data Science and its Applications  
**University:** University of Essex, United Kingdom  
**Project:** MSc Dissertation
