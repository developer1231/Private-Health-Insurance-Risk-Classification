## Project Title: Classified Health Insurance

**Affiliation:**
The Institute for Computing and Information Sciences, Radboud University, Nijmegen, Gelderland, Netherlands

## Abstract
This project focuses on addressing the increasing competitiveness among private health insurers by exploring three classifiers: Random Forest, Decision Tree, and Logistic Regression. The goal is to categorize individuals as Low or High Risk based on predictions of potential medical costs, enabling private insurers to selectively offer insurance for maximum profit. Our findings indicate that Random Forest exhibits the best overall performance, followed by Logistic Regression and then Decision Tree.

## Keywords
Classification, Health Care Classification, Private Insurance, Classifier Model Comparison, Logistic Regression, Decision Tree, Random Forest, AI, Model Evaluation, Model Analysis, Health Data Analysis, Healthcare Analytics, Data Preprocessing, Data Visualization.

## 1. Problem Introduction

### 1.1 Research Problem
The increasing competitiveness in the private health insurance market poses challenges for insurers aiming to provide quality health coverage while maximizing profits. As more individuals seek private insurance, there is a growing need to selectively choose clients to manage costs. Private insurers have the discretion to turn down high-risk clients, those likely to incur significant medical expenses, to maintain profitability. The research aims to develop a classification model that assists insurers in selectively offering insurance to maximize company profit.

### 1.2 Purpose of the Research
The objective is to categorize prospective clients into 'Low Risk' or 'High Risk' based on various factors such as age, medical history, and state of residence. By creating an accurate classification model, private insurers can make informed decisions about offering insurance, optimizing profitability.

## 2. Related Works

### 2.1 Previous Concepts
While exploring datasets for our model, we encountered a researcher addressing a similar issue. The researcher focused on predicting healthcare costs using machine learning techniques. Our work extends and builds upon this research, using a more complex dataset and employing three different classifiers.

## 3. Research Steps

### 3.1 Research Dataset
We utilized three datasets: 'names.xlsx,' 'hospitalizations.csv,' and 'medical_examinations.csv.' These datasets contained customer information, hospitalization data, and health information, respectively.

### 3.2 Pre-processing Methods
Data exploration involved manual examination of datasets, identifying relationships, and handling missing values. Pre-processing steps included data merging, removal of unnecessary columns, outlier removal, and transforming categorical variables. The 'charges' column was transformed to 'Low Risk' or 'High Risk' based on the median.

## 4. Approach

### 4.1 Random Forest
We employed a Random Forest model with hyperparameter optimization, utilizing stratified 100-fold cross-validation for model evaluation.

### 4.2 Logistic Regression
Logistic Regression, based on weighted sum calculations, was used with similar evaluation methods as Random Forest.

### 4.3 Decision Tree
A classic Decision Tree model was also used with depth optimization and 100-fold stratified cross-validation.

### 4.4 Choices
The three algorithms were selected for comparison to assess their relative performance.

## 5. Results

### 5.1 Model Evaluation Techniques
We employed four evaluation techniques: accuracy, confusion matrices, ROC curve, and AUC. Random Forest consistently outperformed the other models across multiple evaluations.

### 5.3 Comparison
Random Forest consistently ranked highest in various evaluation methods, making it the best-performing model in our comparison.

### 5.4 Expectations & Conclusion
The expectation that Random Forest would outperform other models was met. Logistic Regression ranked second, and Decision Tree third in overall performance.

## 6. Improvements
Upon reviewing the project, we identified potential improvements, including exploring alternative methods for handling missing values, more effective hyperparameter optimization, and employing grid search for decision tree-based models.

Overall, our project provides valuable insights into classifier performance in the context of private health insurance, offering a basis for future research and applications in the healthcare industry.
