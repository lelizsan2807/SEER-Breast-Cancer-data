# Breast Cancer Survival Prediction

## Overview

Breast cancer remains one of the most common cancers worldwide, making early risk assessment and outcome prediction critical for improving patient care. This project explores the use of machine learning techniques to predict patient survival outcomes based on clinical and demographic characteristics.

The goal of the project is to develop predictive models that can identify patterns associated with survival outcomes while demonstrating a complete data science workflow, including data preparation, exploratory analysis, feature engineering, model development, evaluation, and visualization.

---

## Business Problem

Healthcare organizations generate large volumes of patient data that can be leveraged to support clinical decision-making. Predictive analytics can help identify high-risk patients, prioritize interventions, and improve treatment planning.

This project investigates whether patient characteristics and clinical indicators can be used to predict survival outcomes through machine learning models.

---

## Dataset

The dataset was obtained from the Surveillance, Epidemiology, and End Results (SEER) Program of the National Cancer Institute (NCI).

It contains information about female patients diagnosed with infiltrating duct and lobular breast cancer, including demographic information, tumor characteristics, lymph node involvement, and survival outcomes.

### Features Included

- Age
- Tumor Size
- Race
- Marital Status
- T Stage
- N Stage
- Number of Examined Regional Nodes
- Number of Positive Regional Nodes
- Survival Months
- Other clinical indicators

### Target Variable

- Status (Alive / Dead)

---

## Project Objectives

- Understand the factors associated with breast cancer survival outcomes.
- Perform exploratory data analysis (EDA) to uncover trends and relationships.
- Prepare and transform clinical data for machine learning.
- Develop predictive classification models.
- Evaluate model performance using standard machine learning metrics.
- Communicate findings through visualizations and data storytelling.

---

## Technologies Used

### Programming

- Python
- Jupyter Notebook

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn

### Version Control

- Git
- GitHub

---

## Methodology

### 1. Data Understanding

The dataset was explored to understand feature distributions, identify missing values, detect inconsistencies, and evaluate data quality.

### 2. Exploratory Data Analysis (EDA)

Key analyses included:

- Survival distribution analysis
- Age distribution by survival status
- Tumor size analysis
- Correlation analysis
- Feature relationship exploration
- Identification of potential predictive variables

### 3. Data Preprocessing

The preprocessing pipeline included:

- Handling missing values
- Encoding categorical variables
- Feature engineering
- Feature scaling (if applicable)
- Train-test split preparation

### 4. Model Development

Several machine learning classification models were trained and compared, including:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 5. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Performance comparisons were used to identify the most effective predictive approach.

---

## Results

The project demonstrated that machine learning techniques can successfully identify patterns associated with breast cancer survival outcomes.

### Key Findings

- Certain clinical indicators showed stronger predictive power than demographic variables.
- Feature engineering improved model performance.
- Ensemble models provided competitive classification results.
- Data preprocessing had a significant impact on predictive accuracy.
- Visual analysis helped identify relationships between tumor characteristics and patient outcomes.

> **Note:** Model performance metrics will be updated as experimentation and tuning continue.

---

## Repository Structure

```text
breast-cancer-survival-prediction/
│
├── README.md
├── data/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_modeling.ipynb
│
├── images/
│
├── requirements.txt
└── .gitignore
```

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation optimization
- Feature importance analysis
- Model explainability using SHAP
- Additional classification algorithms
- Deployment as an interactive web application
- Integration with healthcare analytics dashboards

---

## Key Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preparation
- Feature Engineering
- Statistical Analysis
- Machine Learning
- Predictive Modeling
- Data Visualization
- Model Evaluation
- Python Programming
- Data Storytelling

---

## Sample Visualizations

Add screenshots from your notebooks here:

### Survival Distribution

![Survival Distribution](images/survival_distribution.png)

### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

### ROC Curve

![ROC Curve](images/roc_curve.png)

### Feature Importance

![Feature Importance](images/feature_importance.png)

---

## Author

### Lucía Elizondo Sancho

- LinkedIn: [Add LinkedIn URL]
- GitHub: [Add GitHub URL]

---

## License

This project is intended for educational and portfolio purposes.
