# ❤️ Heart Disease Prediction using Machine Learning

This project uses machine learning models to predict the presence of heart disease in patients based on clinical and physiological data. It is implemented in a Jupyter Notebook using Python, with step-by-step data preprocessing, visualization, model training, and evaluation.

---

## 🧠 Objective

To develop and evaluate machine learning models that can **predict whether a patient has heart disease** using features such as age, sex, chest pain type, blood pressure, cholesterol levels, and more.

---

## 📊 Dataset

- **Source:** UCI Machine Learning Repository – [Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Instances:** 303
- **Target Variable:** `target` (1 = heart disease, 0 = no heart disease)

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** – data handling
- **NumPy** – numerical operations
- **Matplotlib** – visualization
- **Scikit-learn** – model training and evaluation
- **Google Colab / Jupyter Notebook** – development environment

---

## 📌 Features Used

- `age`, `sex`, `cp` (chest pain type), `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`, and `target`.

---

## 📈 Machine Learning Models Applied

| Model                  | Accuracy Score |
|------------------------|----------------|
| Logistic Regression    | ✅ Reasonable baseline classifier  
| K-Nearest Neighbors    | 🟡 Tuned using cross-validation  
| Decision Tree          | 🟠 Easily interpretable  
| Random Forest          | ✅ High accuracy and robustness  
| Support Vector Machine | ✅ Great performance after scaling  

---

## 📋 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score

---

## 🧪 Steps Performed

1. **Data Exploration** – Checked for missing values, distributions, and correlations.
2. **Preprocessing** – Handled categorical variables and feature scaling.
3. **Model Training** – Applied multiple classifiers and compared results.
4. **Evaluation** – Analyzed performance with metrics and visualizations.
5. **Conclusion** – Identified the best-performing model for prediction.


