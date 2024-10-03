# Diabetes Prediction Using Machine Learning
# Project Overview
This project involves the application of machine learning algorithms to predict the incidence of diabetes based on demographic, physiological, and clinical features. It is part of the MB140 - Introduction to Applied Statistics course at Kristiania University College, conducted during the Spring 2024 semester.
# Research Objective
The primary objective of this research is to evaluate various machine learning models and determine the most effective algorithm for predicting diabetes. We explore several machine learning techniques including Decision Trees, Random Forests, Logistic Regression, Support Vector Machines (SVM), and Gradient Boosting.
# Dataset
The dataset used in this project is sourced from Kaggle and is titled "Diabetes Prediction Dataset". It contains medical and demographic data from patients, indicating their diabetes status. The dataset features include age, gender, BMI, hypertension, heart disease, smoking history, HbA1c level, and blood glucose level.
# Methodology
The project is structured as follows:
1.	Data Collection and Preprocessing:
o	Data cleaning and transformation to prepare for analysis.
o	Handling missing values and encoding categorical variables.
2.	Exploratory Data Analysis (EDA):
o	Visualizing distributions and relationships between features.
o	Computing statistical summaries to understand data characteristics.
3.	Model Building and Training:
o	Splitting the data into training and testing sets.
o	Training models using various supervised learning algorithms.
4.	Model Evaluation:
o	Evaluating model performance using accuracy, precision, recall, F1 score, and AUC-ROC.
o	Comparison of model outcomes to select the best performer.
# Results
Our analysis shows that Gradient Boosting and Decision Trees perform exceptionally well, with Gradient Boosting slightly edging out with superior AUC-ROC values. The results underscore the potential of machine learning in medical predictive analytics, particularly for diabetes prediction.
# Libraries Used
•	pandas: For data manipulation and analysis.
•	numpy: For numerical data operations.
•	matplotlib and seaborn: For data visualization.
•	sklearn: For implementing machine learning algorithms.
# How to Run the Notebook
1.	Clone this repository to your local machine.
2.	Ensure that you have Jupyter Notebook installed, or use Google Colab to open the .ipynb files.
3.	Install all required libraries using pip install -r requirements.txt.
4.	Run the notebook cells sequentially to replicate the analysis.

