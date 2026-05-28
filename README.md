# Machine Learning Classification Pipeline with FastAPI & Streamlit

## 📝 Project Overview
This project builds an end-to-end Machine Learning classification pipeline using the **Adult Census Income Dataset**. The goal is to predict whether an individual's annual income exceeds $50K or is less than/equal to $50K per year, based on various demographic and employment attributes like age, education, occupation, and hours worked per week.

The model is operationalized via a **FastAPI backend REST API** that serves predictions, and an interactive, user-friendly web interface built using **Streamlit** for real-time inference.

## 📊 Model Comparison & Accuracies
All models were trained and evaluated inside a single Jupyter Notebook using robust Scikit-Learn Pipelines (handling data imputation, scaling, and categorical one-hot encoding smoothly).

Here is the comparison of accuracies achieved by different classification models:

* **Logistic Regression:** 84.21%
* **Decision Tree (Best Model):** **85.54%**
* **Support Vector Classifier (SVC):** 83.85%
* **KNN Classifier:** 82.93%

### 🏆 Best Performing Model Details
* **Model:** Decision Tree Classifier (Hyperparameter tuned with max_depth=10)
* **Accuracy:** ~85.54%
* **Saved Artifact:** `model.pkl` (Contains the full preprocessing + prediction pipeline)

## 🔗 Live Deployment Demo Link
Aap is project ka live functional web demo yahan dekh sakte hain:
👉 **[https://github.com/muskan-muhammad-amir/Income-Classification-Pipeline](https://github.com/muskan-muhammad-amir/Income-Classification-Pipeline)** *(Note: Kindly replace this text with your exact Streamlit Share URL once deployed)*

## 💻 Steps to Run the Project Locally

### 1. Clone the repository
```bash
git clone [https://github.com/muskan-muhammad-amir/Income-Classification-Pipeline.git](https://github.com/muskan-muhammad-amir/Income-Classification-Pipeline.git)
cd Income-Classification-Pipeline


