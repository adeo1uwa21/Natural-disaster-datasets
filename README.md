# Natural Disaster Impact Prediction 🌍🌪️

## Project Overview
This repository contains a machine learning classification project designed to predict the human impact severity of historical natural disasters. By analyzing global disaster data (such as droughts, earthquakes, and floods), the models predict whether a specific disaster event resulted in a high human impact (affected populations > 0).

This project was developed as part of a Machine Learning assessment to demonstrate proficiency in data preprocessing, model training, and performance evaluation.

## Dataset
* **File:** `natural-disaster.csv`
* **Description:** Contains historical records of various natural disasters, including data on geographic location, economic damages, and human casualties (deaths, injuries, and affected populations). 
* *Note: The target variable `Has_High_Impact` was engineered for binary classification purposes.*

## Project Workflow
The project is structured into four main tasks:
1. **Data Inspection:** Analyzing the shape, dimensions, and identifying missing values within the raw dataset.
2. **Data Preparation:** * Imputing missing numerical values with `0`.
   * Engineering the binary target variable (`Has_High_Impact`).
   * Preventing data leakage by dropping highly correlated continuous target variables.
   * Encoding categorical features using `LabelEncoder`.
3. **Model Building:** Training three distinct classification models using an 80/20 train-test split:
   * Logistic Regression
   * Decision Tree Classifier
   * Random Forest Classifier
4. **Evaluation:** Assessing model performance using:
   * Accuracy
   * Precision
   * F1-Score
   * Confusion Matrices (visualized with Seaborn/Matplotlib)

## Technologies & Libraries Used
* **Python 3**
* **Pandas & NumPy:** Data manipulation and analysis
* **Scikit-Learn:** Machine learning algorithms and evaluation metrics
* **Matplotlib & Seaborn:** Data visualization

## Results Summary
Ensemble models demonstrated the highest predictive capability on this dataset. The **Random Forest Classifier** emerged as the optimal model, outperforming both the Decision Tree and Logistic Regression models in Accuracy, Precision, and F1-Score, while effectively minimizing false classifications.

## Author
* **[Your Name]** * **Matric No:** [Your Matric Number]
* **Department:** [Your Department]
