# Heart-Disease-Prediction-Using-Machine-Learning-With-GUI
This repository contains a Jupyter Notebook that demonstrates the process of predicting heart disease using various machine learning algorithms. The project involves data preprocessing, model selection, training, and evaluation to create a predictive model based on a heart disease dataset.

## Project Overview
The objective of this project is to build a machine learning model that can accurately predict the presence of heart disease in patients. The dataset used in this project is the Heart Disease Dataset, which contains various features related to patients' health metrics.

## Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository and consists of several attributes related to heart disease. The key features include:

age: Age of the patient

sex: Gender of the patient

cp: Chest pain type

trestbps: Resting blood pressure

chol: Serum cholesterol in mg/dl

fbs: Fasting blood sugar > 120 mg/dl

brestecg: Resting electrocardiographic results

thalach: Maximum heart rate achieved

exang: Exercise-induced angina

oldpeak: ST depression induced by exercise relative to rest

slope: The slope of the peak exercise ST segment

ca: Number of major vessels (0-3) colored by fluoroscopy

thal: Thalassemia


target: Target variable indicating the presence of heart disease


# Steps Followed
# 1. Importing Libraries
The first step involves importing necessary libraries for data manipulation, visualization, and model building. Key libraries include:

pandas for data manipulation

numpy for numerical computations

matplotlib and seaborn for data visualization

scikit-learn for model building and evaluation

# 2. Loading the Dataset
The dataset is loaded using pandas and explored to understand the structure and contents.

# 3. Data Preprocessing
Handling Missing Values:  The dataset is checked for missing values, and appropriate steps are taken to handle any missing data. In this case, the dataset has no missing values.

Handling Duplicate Values: Duplicate entries are checked and removed to ensure the dataset is clean.

Data Visualization: Various features are visualized to understand their distribution and relationship with the target variable.

# 4. Feature Selection
Relevant features are selected based on their importance in predicting the target variable. Feature scaling is also applied to standardize the range of independent variables.

# 5. Splitting the Data
The dataset is split into training and testing sets to evaluate the performance of the model.

# 6. Model Selection and Training
Several machine learning algorithms are tested to find the best-performing model. The models used include:

# Logistic Regression
# K-Nearest Neighbors (KNN)
# Support Vector Machine (SVM)
# Random Forest
# Decision Tree
Each model is trained on the training set, and hyperparameters are tuned using cross-validation.

# 7. Model Evaluation
The models are evaluated on the test set using various metrics such as accuracy, precision, recall, and F1-score. The model with the best performance is selected as the final model.

# 8. Saving the Model
The best model is saved for future use using joblib.
