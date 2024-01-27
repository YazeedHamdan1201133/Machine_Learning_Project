# Predictive Modeling for Obesity Classification

## Introduction
This project focuses on building a predictive model using a dataset about obesity, with the goal of effectively predicting obesity categories based on various factors like age, height, weight, and more. This work aims to better understand what contributes to obesity and demonstrates how machine learning can be applied in health-related areas&#8203;``【oaicite:5】``&#8203;.

## Dataset
The dataset includes a mix of numerical and categorical variables with seven features and 1000 examples, such as age, height, weight, BMI, PhysicalActivityLevel, and Gender. The target variable, ObesityCategory, classifies individuals into four different obesity categories, making this a classification task&#8203;``【oaicite:4】``&#8203;.

## Models Explored
Three different types of models were used in this project:
- **K-Nearest Neighbors (KNN)**: A simple model making predictions based on the closest data points. Tested with k=1 and k=3 settings.
- **Random Forest**: Known for accuracy and reliability, this model works by creating several decision trees and combining their results. The number of trees (n_estimators) was adjusted for optimal performance.
- **Support Vector Machine (SVM)**: Strong for datasets with many features, SVM can be customized with different kernel functions. The C parameter was fine-tuned to control the model's complexity&#8203;``【oaicite:3】``&#8203;.

## Evaluation Metrics
The models' performance was evaluated using the following metrics:
- **Accuracy**: Measures the proportion of correctly predicted examples.
- **Precision and Recall**: Provide insights into the accuracy of the model's predictions and its ability to find all true cases.
- **F1-Score**: A balance of precision and recall in one number&#8203;``【oaicite:2】``&#8203;.

## Experiments and Results
- **KNN with k=1**: Showed perfect learning from training data but less effective on test data, suggesting overfitting.
- **KNN with k=3**: Slightly better performance on test data, indicating better generalization.
- **Random Forest and SVM**: Performance was evaluated based on the number of trees for Random Forest and the C parameter for SVM. Random Forest showed higher accuracy and fewer misclassifications compared to SVM&#8203;``【oaicite:1】``&#8203;.

## Conclusions and Discussion
The analysis concluded that the Random Forest model outperformed the SVM model and KNN for this dataset. The Random Forest model's ensemble approach produced a more generalized and robust model, performing well with complex feature relationships. KNN with k=3 yielded better results than k=1, reducing overfitting and improving performance on test data&#8203;``【oaicite:0】``&#8203;.

