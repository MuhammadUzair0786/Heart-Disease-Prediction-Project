# ❤️ Heart Disease Prediction with PCA Optimization

This project predicts the presence of heart disease using supervised machine learning algorithms and demonstrates the impact of dimensionality reduction with **PCA (Principal Component Analysis)** on model accuracy and computational efficiency.

---

## 🚀 Project Workflow

1. **Load Data:** Import the heart disease dataset using Pandas.
2. **Outlier Removal:** Detect and remove outliers using the Z-Score method (threshold ±3).
3. **Encoding Categorical Variables:**
   - **Label Encoding** for multi-class features (`ChestPainType`, `RestingECG`, `ST_Slope`)
   - **One-Hot Encoding** for binary features (`Sex`, `ExerciseAngina`)
4. **Feature Scaling:** Apply StandardScaler to normalize numerical features.
5. **Model Training & Evaluation:**
   - Train and evaluate **Logistic Regression**, **Support Vector Machine (SVM)**, and **Random Forest Classifier**.
   - Assess model performance before and after applying PCA for dimensionality reduction.
6. **Result Comparison:** Analyze the trade-off between accuracy and computational efficiency with and without PCA.

---

## 🧠 Key Concepts Applied

- **Outlier Detection:** Improve model reliability by removing extreme values using Z-Score.
- **Encoding:** Properly handle categorical variables with Label and One-Hot Encoding.
- **Feature Scaling:** Standardize features for optimal model performance.
- **Model Comparison:** Evaluate and compare multiple machine learning algorithms.
- **Dimensionality Reduction:** Use PCA to reduce feature space while retaining maximum variance.

---

## 🔥 Results Overview

| Model                   | Accuracy Without PCA | Accuracy With PCA |
|-------------------------|---------------------|------------------|
| Logistic Regression     | ✅ Higher           | 🔻 Slightly lower|
| Support Vector Machine  | ✅ Higher           | 🔻 Slightly lower|
| Random Forest           | ✅ Higher           | 🔻 Slightly lower|

- **Observation:**  
  Applying PCA slightly reduces accuracy but decreases computational load, which is beneficial for larger datasets.

---

## 📁 Folder Structure

```
Heart-Disease-Prediction-PCA/
├── heart_disease_prediction.ipynb
├── README.md
└── dataset/
    └── heart.csv
```

---

## 💻 Tech Stack

- Python
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📌 How to Run

1. Clone the repository and navigate to the project folder.
2. Ensure all required libraries are installed (`pip install -r requirements.txt`).
3. Open `heart_disease_prediction.ipynb` in Jupyter Notebook.
4. Run each cell step by step to follow the workflow and view results.

---

## 📊 License

This project is for educational purposes.

---

This notebook is a practical guide for beginners to understand and apply data preprocessing, machine learning, and dimensionality reduction for heart