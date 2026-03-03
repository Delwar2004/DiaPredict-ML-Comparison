# 🩺 DiaPredict — Comparative Analysis of Diabetes Classification Models
**An End-to-End Machine Learning Study on Clinical Prediction Stability & Model Generalization**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn)
![Status](https://img.shields.io/badge/Version-4.0-green?style=for-the-badge)

---

## 📌 Project Overview
Early detection of chronic diseases plays a critical role in reducing long-term health complications. **DiaPredict** is an end-to-end Machine Learning research project that investigates how different classification algorithms perform on real medical diagnostic data (**Pima Indians Diabetes Dataset**).

Instead of chasing raw accuracy, this project emphasizes:
* **Model Stability** & **Generalization Ability**
* **Overfitting Detection**
* **Clinical Reliability Analysis**

---

## 🎯 Key Objectives
* **🔬 Algorithm Comparison:** Evaluate SVM, Random Forest, KNN, and Logistic Regression.
* **⚖️ Model Generalization:** Identify models that perform consistently on unseen patients.
* **📊 Data Standardization:** Normalize feature distributions using `StandardScaler`.
* **🧠 Reliability Analysis:** Understand which model is safest for real-world prediction.

---

## 🏗️ Technical Pipeline
The project follows a rigorous data science workflow:
`Dataset` → `EDA` → `Preprocessing` → `Standardization` → `Model Training` → `Evaluation` → `Comparison`



1. **Exploratory Data Analysis (EDA):** Feature relationship analysis between Glucose, BMI, and Age.
2. **Preprocessing:** Scaling features to prevent dominance of large numerical values.
3. **Training & Validation:** Split applied to four classifiers trained independently.

---

## 📊 Experimental Results (Version 4.0 Benchmark)

| Model | Training Accuracy | Test Accuracy | Status |
| :--- | :--- | :--- | :--- |
| **Support Vector Machine (SVM)** | **77.2%** | **76.6%** | **🏆 Most Stable** |
| **Logistic Regression** | 78.0% | 76.6% | ✅ High Reliability |
| **Random Forest** | 100.0% | 77.9% | ⚠️ Overfitting Detected |
| **K-Nearest Neighbors (KNN)** | 83.5% | 74.6% | ⚖️ Moderate Performance |

### 🧠 Critical Insights
* **⚠️ Overfitting Observation:** Random Forest achieved perfect training accuracy (1.0) but showed reduced testing performance, indicating the model memorized patterns.
* **🏆 Generalization Winner:** **SVM** demonstrated minimal performance gap between training and testing, indicating real-world robustness.
* **📌 Key Learning:** In medical AI systems, **Stability > Maximum Accuracy**.

---

## 💻 Installation & Usage

### 1. Clone the Repository
```bash
git clone [https://github.com/Delwar2004/DiaPredict-ML-Comparison/tree/main]
2. Install Dependencies
Bash
pip install pandas numpy scikit-learn
3. Run the Project
Launch Jupyter Notebook.

Open Diabetes_Prediction.ipynb and execute all cells.

🚀 Future Roadmap
[ ] 🔧 Hyperparameter tuning using GridSearchCV.

[ ] 🌐 Model deployment with Streamlit Web App.

[ ] 💾 Model serialization using Pickle.

[ ] 📊 Advanced metrics: ROC Curve & Confusion Matrix Visualization.

👨‍💻 Author
Md. Delwar Husen
Department of ICT
Bangladesh University of Professionals (BUP)
Interests: Machine Learning | Heathcare in AI | Deep Learning

⭐ Support the Project
If you find this project helpful, feel free to Star the repository and share it!
