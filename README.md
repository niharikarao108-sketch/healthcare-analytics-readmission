# Healthcare Analytics – 30-Day Readmission Prediction

## Project Overview

This is a personal healthcare analytics project developed to explore how
data analytics and machine learning can be applied to hospital readmission
analysis.

The project analyzes patient encounter data to identify factors associated
with 30-day hospital readmission and compares different machine learning
approaches for predicting readmission risk.

## Objectives

- Analyze patient and hospital encounter data
- Explore factors associated with 30-day readmission
- Apply statistical tests to identify meaningful relationships
- Build and compare classification models
- Evaluate models using accuracy, precision, recall and F1-score
- Understand the impact of class imbalance on healthcare prediction

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook

## Analysis Performed

### Exploratory Data Analysis
- Patient demographics
- Department-wise patient volume
- Treatment cost
- Length of stay
- Number of procedures
- ICU admission
- 30-day readmission patterns

### Statistical Analysis
- Chi-square test
- Mann-Whitney U test
- Other statistical comparisons used to examine relationships between
  patient characteristics and readmission

### Machine Learning

The project explores:

- Logistic Regression
- Class-balanced Logistic Regression
- Random Forest

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Key Learning

A major learning from the project was the importance of looking beyond
accuracy when working with imbalanced healthcare data. A model can achieve
high accuracy while performing poorly at identifying patients who are
actually readmitted.

The project therefore compares model performance using recall, precision,
F1-score and confusion matrices rather than relying on accuracy alone.

## Business / Healthcare Relevance

The analysis demonstrates how healthcare analytics can support:

- Identification of patients at higher readmission risk
- Better understanding of factors associated with readmission
- Data-driven hospital management decisions
- More informed use of predictive analytics in healthcare

## Limitations

- The dataset is used for learning and analytical practice.
- The model should not be interpreted as a clinical decision-support tool.
- Predictive performance depends on the quality and characteristics of
  the available data.
- Further validation using real-world clinical data would be required
  before any operational or clinical use.

## Author

Personal project by Dr. K Niharika Rao  
Dentist | MBA – Hospital & Health Management

This project was undertaken as a self-learning initiative to develop
practical skills in healthcare analytics, statistics and machine learning.

