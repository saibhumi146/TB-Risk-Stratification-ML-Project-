# 🦠 Life-Course TB Risk Stratification

### 📌 Project Overview
This repository contains a complete end-to-end Machine Learning pipeline and Clinical Decision Support Web Application. The objective of this project is to predict the risk of Tuberculosis in older age (65+) based on historical childhood exposure (ages 0-14) using data from the World Health Organization (WHO).

This project was built following a structured 5-module architecture to clean data, train multiple algorithms, and provide a user-friendly interactive dashboard for risk stratification.

### 🛠️ Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, XGBoost
* **Visualization:** Matplotlib, Seaborn
* **Web UI:** Gradio

### 🧠 Machine Learning Models
To ensure high predictive accuracy and capture complex life-course risk patterns, three distinct algorithms were trained and evaluated:
1. **Logistic Regression** (Baseline classification)
2. **Random Forest** (Capturing non-linear relationships)
3. **XGBoost** (Primary model utilizing gradient boosted decision trees)

### 🖥️ Dashboard Architecture (5 Modules)
The project includes a functional web UI built with Gradio, divided into five core modules:
* **Module 1: Dataset Management** - Uploads and cleans WHO historical statistics.
* **Module 2: Data Analysis** - Explores the correlation between childhood exposure and older-age incidence.
* **Module 3: ML Models** - Trains and compares Logistic Regression, Random Forest, and XGBoost performance metrics (Accuracy, ROC-AUC).
* **Module 4: Risk Stratification** - An interactive clinical tool predicting future TB risk based on customized exposure baselines.
* **Module 5: Reports** - Exportation of evaluation results for research documentation.

### 🚀 How to Run
1. Open the `tb_risk_model.ipynb` file in Google Colab.
2. Upload the WHO Tuberculosis CSV dataset into the Colab environment.
3. Run all cells to process the data, train the models, and generate the live Gradio web dashboard link.
