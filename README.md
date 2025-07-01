# ❤️ Heart Disease Prediction with PCA Optimization

This project aims to predict the presence of heart disease using supervised machine learning algorithms. It also demonstrates how dimensionality reduction using **PCA (Principal Component Analysis)** impacts model accuracy and computational efficiency.

---

## 🚀 **Project Workflow**

- ✅ Load the heart disease dataset into Pandas.
- ✅ Remove outliers using the **Z-Score method** (threshold ±3).
- ✅ Convert categorical columns using:
  - **Label Encoding** for multi-class features (`ChestPainType`, `RestingECG`, `ST_Slope`)
  - **One-Hot Encoding** for binary features (`Sex`, `ExerciseAngina`)
- ✅ Apply **Standard Scaling** to normalize the data.
- ✅ Train and compare machine learning models:
  - **Logistic Regression**
  - **Support Vector Machine (SVM)**
  - **Random Forest Classifier**
- ✅ Evaluate models before and after applying **PCA** for dimensionality reduction.
- ✅ Compare results to understand the trade-off between accuracy and computational efficiency.

---

## 🧠 **Key Concepts Applied**

- **Outlier Detection:** Using Z-Score to improve model reliability.  
- **Encoding:** Handling categorical variables correctly using Label and One-Hot Encoding.  
- **Scaling:** Standardizing features for better model performance.  
- **Model Comparison:** Evaluate models with and without PCA.  
- **Dimensionality Reduction:** Reduce feature space while retaining maximum variance using PCA.

---

## 🔥 **Results Overview**

| Model                 | Accuracy Without PCA | Accuracy With PCA |
|-----------------------|----------------------|-------------------|
| Logistic Regression    | ✅ Higher            | 🔻 Slightly lower |
| Support Vector Machine | ✅ Higher            | 🔻 Slightly lower |
| Random Forest          | ✅ Higher            | 🔻 Slightly lower |

- **Observation:** PCA slightly reduces accuracy but reduces computational load — beneficial for large datasets.

---

## 📁 **Folder Structure**
📦 Heart-Disease-Prediction-PCA
┣ 📜 heart_disease_prediction.ipynb
┣ 📜 README.md
┣ 📜 dataset/heart.csv


---

## 💻 **Tech Stack**

- Python
- Pandas
- Numpy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## 🚀 **How to Run**

1. Clone the repository:
```bash
git clone https://github.com/MuhammadUzair0786/Heart-Disease-Prediction-Project.git



