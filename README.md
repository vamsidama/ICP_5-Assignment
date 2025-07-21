# ICP_5-Assignment

# ICP 5 – Machine Learning Pipeline with Iris Dataset
Name: Dama Vamsi
Course: Big Data Analytics
Reg No: 700771673

## Project Overview

This assignment demonstrates a complete machine learning pipeline using the Iris dataset.
The pipeline integrates preprocessing, dimensionality reduction, and model selection with hyperparameter tuning.

##  Dataset

- Dataset Used:** Iris dataset from `sklearn.datasets`

##  Technologies & Libraries

- Python
- Scikit-learn
- Pandas
- NumPy

##  Methodology

1. Data Loading** – Iris dataset was imported directly from `sklearn`.
2. Preprocessing** – Missing values handled using `SimpleImputer`, features standardized using `StandardScaler`.
3. Dimensionality Reduction** – Applied `PCA` for reducing feature space.
4. Modeling** – Five models were evaluated using:
   - SVC
   - Random Forest
   - Logistic Regression
   - Perceptron
   - KNN
5. Tuning – Hyperparameter tuning via `GridSearchCV` and `RandomizedSearchCV`.
6. Evaluation – The models were compared based on their cross-validation scores.

## Results

Each model's best parameters and scores were recorded. 
This pipeline can be extended to other datasets easily.

--- The End ---
