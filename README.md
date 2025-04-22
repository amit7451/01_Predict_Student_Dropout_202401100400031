# 🎓 Student Dropout Prediction using Machine Learning

This project aims to predict whether a student is at risk of dropping out based on factors like attendance, grades, and participation using a classification model (Logistic Regression).

---

## 📌 Problem Statement

Predict whether a student will **drop out** based on their **attendance**, **grades**, and **participation**. This is a binary classification problem (0 = Not At Risk, 1 = At Risk).

---

## 🧠 Approach

We follow a traditional machine learning pipeline:

- Data Preprocessing
- Feature Engineering
- Train-test split
- Logistic Regression
- Evaluation with Accuracy, Precision, Recall, F1 Score
- Visualization using Confusion Matrix

---

## 🗃️ Dataset

The dataset contains the following columns:

- `attendance`  
- `grades`  
- `participation`  
- `dropout_risk` (Target Variable: yes/no)

---

## 🧹 Data Preprocessing

1. Checked for missing values.
2. Applied one-hot encoding to convert `dropout_risk` to numeric.
3. Used `StandardScaler` to scale numeric features.
4. Split data into training (80%) and testing (20%) sets.

---

## 🧪 Model Implementation

We used **Logistic Regression** for classification. It is simple, fast, and effective for binary classification problems like this.

---

## 📊 Evaluation Metrics

The model was evaluated using:

- ✅ **Accuracy**
- 📌 **Precision**
- 🎯 **Recall**
- 📐 **F1 Score**
- 📉 **Confusion Matrix** (heatmap)

---

## 🖼️ Screenshots




> 🔎 *These screenshots help visualize the overall classification performance and problem scope.*

---

## 📌 Results and Analysis

- The Logistic Regression model gave **reasonable accuracy** on the test set.
- The **confusion matrix** showed a good balance between false positives and false negatives.
- **Precision** and **recall** scores indicate the model can reliably flag potential dropouts.

---

## ✅ Conclusion

Logistic Regression was effective in predicting student dropout risk. While this baseline model works well, future improvements may include:

- Using Random Forest or Gradient Boosting
- Addressing class imbalance
- Adding more student features (e.g., socio-economic background, feedback, etc.)

---

## 🙌 Credits

- 📂 Dataset from local drive (`student_dropout.csv`)
- 🐍 Libraries: Pandas, Scikit-learn, Seaborn, Matplotlib
- 👨‍💻 Developed in Google Colab

