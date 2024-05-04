## Overview:

In this third practical application assignment, the goal is to compare the performance of different classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines) using a dataset related to the marketing of bank products over the telephone.

## Data:

The dataset used in this project comes from the UCI Machine Learning repository. It consists of data from a Portuguese banking institution and includes the results of multiple marketing campaigns. Additional information on the data and features can be found in the accompanying article within the .zip file provided.

## Business Problem
The main objective of this project is to make the Portuguese bank's telemarketing campaign more effective. 
By performing data analysis, EDA and visualization we can determine the target customer profile which have the most success rate of subscribing to the term.  

We can identify  clients that have higher chance to subscribe for a term deposit and focus marketing effort on such clients. We also build and compare different classfication models to predict which clients are more likely to subscribe for term deposits (binary outcome: yes or no) based on various demographic and marketing campaign-related features.
This prediction can aid in optimizing marketing strategies and resource allocation for future campaigns, ultimately improving the bank's efficiency in acquiring term deposits.

## Repository Contents:

- Jupyter Notebook: Contains the code and analysis.
  https://github.com/pvvam/PA_17_1_Comparing_Classfiers/blob/main/prompt_III.ipynb
  
- README.md: Overview of the project, including the problem statement, data description, deliverables, and repository contents.
- Dataset: Data used for analysis (should be included in the repository or linked to the source).

## Conclusion:

By conducting exploratory data analysis and implementing various algorithms, we were able to gain valuable insights into the telemarketing dataset and develop a predictive model with a high level of accuracy.

The below classifiers were compared in this analysis.
- K-Nearest Neighbors (KNN) Classifier
- Logistic Regression Classifier
- Decision Tree Classifier
- Support Vector Machine (SVM) Classifier

Based on the evaluation results and our specific requirements, we can select the classifier that best meets your needs in terms of performance, interpretability, and computational efficiency.

From the evaluated classifiers, SVM and Logistic Regression achieved the highest accuracy scores, around 91%.
SVM classifier after hyperparameter tuning have a good scores.
Decision Tree Classifier showed relatively lower accuracy but provided insights into feature importance.
KNN classifier had worst accuracy score in three clasifiers.

If idenitfying the factors are critical and interpreatability is concerned, Decision tree is a good choice since the decision-making process is represented as a tree structure. Als for computational efficiency, Decision Tree is a good choice with lowest train time.

This analysis demonstrates the application of various machine learning models to predict term deposit subscription based on client features and marketing campaign details. By leveraging these predictive models, the bank can optimize its marketing efforts and resource allocation, ultimately leading to improved efficiency and effectiveness in acquiring term deposits. 
