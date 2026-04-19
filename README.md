# 🚢 Titanic Survival Prediction (ML Preprocessing & Pipeline)

## 📌 Project Overview
This project focuses on building a strong data preprocessing pipeline for the Titanic dataset before applying machine learning models.  
It demonstrates best practices used in real-world ML workflows such as handling missing values, avoiding data leakage, and maintaining data consistency.

---

## 🔍 Key Features
- ✅ Handled missing values using **Median Imputation**
- ✅ Applied **Train-Test Split with Stratification**
- ✅ Prevented **Data Leakage**
- ✅ Built **Numerical & Categorical Pipelines**
- ✅ Used **One-Hot Encoding for categorical features**
- ✅ Clean and structured preprocessing workflow

---

## 🛠️ Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**

---

## 📊 Dataset
- Titanic dataset (fetched using `fetch_openml`)
- Total samples: 1309
- Includes features like:
  - Age
  - Sex
  - Fare
  - Pclass
  - Embarked

---

## ⚙️ Workflow

### 1. Data Loading
- Loaded dataset using `sklearn.datasets.fetch_openml`

### 2. Data Exploration
- Checked missing values using `.isna().sum()`

### 3. Train-Test Split
- Used `train_test_split`
- Maintained class balance using `stratify=y`

### 4. Missing Value Handling
- Numerical → Median Imputation
- Categorical → Constant/Most Frequent

### 5. Feature Transformation
- Numerical pipeline:
  - Imputation
  - Scaling
- Categorical pipeline:
  - Imputation
  - One-Hot Encoding

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/Gauri-2904/titanic-ml-project.git
# this is its clab Link
https://colab.research.google.com/github/Gauri-2904/titanic-ml-project/blob/main/TitanicSurvivalPrediction.ipynb
