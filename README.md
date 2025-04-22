# 01_Predict_Student_Dropout_202401100400031

# 🎓 Student Dropout Prediction



This project uses machine learning techniques to predict the risk of student dropout based on key academic performance indicators such as attendance, grades, and participation. The aim is to help educational institutions identify at-risk students early and take preventive action.

## 📁 Dataset

The dataset contains the following columns:
- `attendance`: Student attendance record
- `grades`: Academic performance scores
- `participation`: Class participation level
- `dropout_risk`: Target label (Yes = at risk, No = not at risk)

The data was preprocessed and encoded using one-hot encoding for categorical values.

## 💡 Problem Statement

Build a classification model to predict whether a student is at risk of dropping out (`dropout_risk`) using features like attendance, grades, and participation.

## 🧠 Approach

1. **Data Preprocessing**
   - Checked for missing values
   - Converted categorical variables using `pd.get_dummies()`
   - Scaled features using `StandardScaler`

2. **Modeling**
   - Used `Logistic Regression` for binary classification
   - Split data into training and test sets (80/20)
   - Evaluated using confusion matrix, accuracy, precision, and recall

3. **Visualization**
   - Confusion matrix displayed using seaborn heatmap
   - 

## 🧾 Installation

To run this project in Google Colab or locally, make sure you have the following dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn







