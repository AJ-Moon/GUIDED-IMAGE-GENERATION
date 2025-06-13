# ✈️ Predicting Air Crash Severity

This project explores the use of machine learning models to predict the **severity of air crashes** based on a range of features such as fatalities, aircraft type, flight phase, and more. By analyzing historical crash data, the model aims to classify incidents as either **severe** or **non-severe**, assisting in understanding critical risk factors and potentially improving aviation safety analytics.

---

## 📚 Project Overview

- **Goal**: Classify air crashes into severity levels.
- **Dataset**: A cleaned and preprocessed version of publicly available aviation accident data.
- **Approach**:
  - Data preprocessing and exploration.
  - Feature selection and encoding.
  - Model implementation and evaluation.
- **Tools Used**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (if applicable), etc.

---

## 🗂️ Repository Contents

| File | Description |
|------|-------------|
| `26100398_PA5_2.ipynb` | Main Jupyter notebook containing the full workflow |
| `README.md` | Project documentation |
| `data/` (optional) | Contains dataset files, if not included in notebook |
| `requirements.txt` (optional) | Python dependencies for running the project |

---

## 📊 Dataset Description

The dataset includes the following types of features:
- **Crash Details**: Date, location, time, etc.
- **Aircraft Info**: Type, operator, etc.
- **Casualties**: Number of fatalities, injuries, survivors.
- **Other Variables**: Flight phase, purpose, etc.
- **Target Variable**: Binary class label (`Severe`, `Non-Severe`)

---

## 🔍 Exploratory Data Analysis

Key EDA tasks performed:
- Visualization of severity class imbalance
- Distribution plots of fatalities and survivors
- Correlation heatmaps for numerical features
- Outlier detection and handling of missing data

---

## 🧠 Machine Learning Models

Multiple machine learning models are trained and evaluated, such as:

- **Logistic Regression**
- **Decision Trees**
- **Random Forest**
- *(Add more if included: SVM, Naive Bayes, Neural Network)*

### 📏 Evaluation Metrics:
- Accuracy
- Precision & Recall
- F1-Score
- Confusion Matrix
- ROC Curve (if used)

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/air-crash-severity-prediction.git
   cd air-crash-severity-prediction
