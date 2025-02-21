# Iris Dataset Project

![image](https://github.com/user-attachments/assets/a72a2bdb-917a-42e5-9f50-3a4e2b0a981a)

## Project Overview

![image](https://github.com/user-attachments/assets/cb96bf45-711e-4f3b-948d-57f7dd5acf39)

The Iris Dataset Analysis and Classification Project focuses on exploring, analyzing, and applying various machine learning models to classify the famous Iris dataset. The Iris dataset contains measurements of iris flowers from three species: Setosa, Versicolor, and Virginica, with four features: sepal length, sepal width, petal length, and petal width.The Iris Dataset Analysis and Classification Project focuses on exploring, analyzing, and applying various machine learning models to classify the famous Iris dataset. The Iris dataset contains measurements of iris flowers from three species: Setosa, Versicolor, and Virginica, with four features: sepal length, sepal width, petal length, and petal width.

## 📢 Note: 
This section provides a surface-level explanation to help understand the general concept of the project. For a detailed understanding of the code execution and the project's full workflow, please refer to the IrisDataset.ipynb notebook associated with the commit message "final" in the repository.---
![image](https://github.com/user-attachments/assets/b26b7123-f1da-40e2-ac31-cbc7b0379996)



## Objectives

The primary objective of this project is to classify the iris species using various machine learning algorithms, evaluate their performance, and visualize the results. The project explores multiple stages including problem analysis, data preprocessing, exploratory data analysis (EDA), model building, hyperparameter tuning, and model evaluation.

Logistic Regression

Random Forest Classifier

Decision Tree Classifier

Baseline Manual Model (for comparison purposes)

# Key Features:

## Problem Analysis

Identified the problem as a classification problem.

The goal is to predict the species of iris flowers based on four numerical features.

## Data Acquisition and Preprocessing

The dataset was initially loaded using Scikit-learn’s built-in function.

To ensure visibility in the repository, the dataset was also saved as a CSV file.

DataFrames were created using Pandas for structured data manipulation.

Feature and target distributions were plotted for each of the four features to understand data patterns.

## Exploratory Data Analysis (EDA)

Univariate plotting was used to explore individual features.

Feature-target interaction was analyzed to identify important predictors.

Pairplots were generated to visualize relationships between features.

Feature correlation was calculated to detect potential multicollinearity.

## Data Preparation

Data was converted into NumPy arrays for compatibility with Scikit-learn models.

The dataset was split into training and testing sets to evaluate model generalization.

## Baseline Model
![image](https://github.com/user-attachments/assets/38de6527-fd4f-4f71-93d2-b6eb943fb673)


A manual baseline model was created using random guessing.

The theoretical accuracy for random guessing was calculated as 33.33% due to the balanced classes.

All subsequent models were expected to surpass this baseline accuracy.
![image](https://github.com/user-attachments/assets/598e43c3-05f4-43ac-8408-86f9dfa385a0)


# Why the Iris Dataset?

The Iris dataset is ideal for classification problems because of its simplicity, balanced class distribution, and the clear distinction between its classes. It provides an excellent benchmark for comparing machine learning algorithms.

![image](https://github.com/user-attachments/assets/0d3f6978-7fd8-47f1-8af0-c48f9d881eb5)

# Modeling Phase

## Model Implementation

Models were trained using both train-test split and 5-fold cross-validation methods.

Implemented classifiers:

Logistic Regression

Random Forest Classifier

Decision Tree Classifier

## Cross-Validation & Performance Evaluation

Cross-validation was used to assess model stability and avoid overfitting.

Predicted versus actual values were compared using scatter plots to visualize misclassifications.

Confusion matrices were plotted for detailed error analysis.

![image](https://github.com/user-attachments/assets/f581195e-7268-4f41-afa9-4a7e2a187bdb)


## Hyperparameter Tuning

Focused on tuning Logistic Regression hyperparameters, particularly the regularization parameter C.

Different values of C were tested: 0.1, 0.3, 0.9, 1.1, 1.9, 100.

Optimal C value (1.9) achieved the highest cross-validation accuracy of 97.27%.

# Evaluation Metrics and Results
## Final Model Performance:

Random Forest:

Cross-Validation Accuracy: 92.73%

Test Set Accuracy: 97.37%

## Decision Tree:

Cross-Validation Accuracy: 93.64%

Test Set Accuracy: 97.37%

## Logistic Regression (C=1.9):

Cross-Validation Accuracy: 97.27%

Test Set Accuracy: 97.37%

Baseline Manual Model: 95.54% accuracy.

# Outcomes
![image](https://github.com/user-attachments/assets/f5ee7e5c-c000-411c-8064-d52bd7f58b3d)


![image](https://github.com/user-attachments/assets/07766b70-15db-4a10-8729-a640fc64a7fb)


## Summarized outcomes
![image](https://github.com/user-attachments/assets/2221a854-df25-404e-9657-9af65970e726)




# Conclusion

All machine learning models outperformed the baseline manual model (95.54%).

Logistic Regression with proper hyperparameter tuning performed best, achieving an accuracy of 97.37% on the test set.

Cross-validation proved essential for assessing model stability and avoiding overfitting.

Random Forest and Decision Tree models showed significant improvement when cross-validation was applied.

Visualizations provided clear insights into model performance and feature interactions.



# Future work
1)Explore other classification algorithms (e.g., Support Vector Machines, K-Nearest Neighbors)

2)Apply dimensionality reduction techniques like PCA to improve performance




