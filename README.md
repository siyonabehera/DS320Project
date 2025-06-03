# Healthcare Data Integration for Hepatitis C Prediction

This project uses clinical lab data to build a predictive model that identifies whether a blood donor is likely to develop Hepatitis C. It was completed as part of the DS320 course at Penn State.

## 👥 Team Members
- Siyona Behera
- Gina Seo

## 📌 Project Overview

Hepatitis C is a viral liver infection that can lead to serious conditions like cirrhosis and cancer. Most patients show no symptoms early on, making early detection critical. Our goal was to analyze lab test data and develop a model to predict Hep-C risk using statistical analysis, data fusion techniques, and machine learning.

## 🧪 Data Preprocessing
- Handled missing values and outliers
- Converted categorical variables (e.g., `Sex`) into numerical format
- Created derived features like ALT/AST ratios
- Addressed class imbalance concerns in the target variable

## 📊 Exploratory Data Analysis
- Visualized feature relationships using pair plots and heatmaps
- Assessed class distributions and statistical significance using the Kruskal-Wallis test
- Applied PCA to evaluate clustering/separation among Hepatitis C categories

## 🤖 Machine Learning Models
- **Logistic Regression**  
  - Accuracy: 96.5%  
  - High precision for Class 2 (Hepatitis), but low recall  
- **Random Forest**  
  - Accuracy: 95.6%  
  - Excellent at predicting healthy donors (Class 0)  
  - Weak recall for Hepatitis cases due to class imbalance

## 💡 Key Findings
- Model predicted healthy donors well, but struggled with minority classes
- ALT and AST levels were useful but not fully predictive
- Data fusion improved predictive power, but more balanced data is needed
- Project shows real-world potential for clinical decision support

## 🛠️ Tools & Libraries
- Python (pandas, scikit-learn, seaborn, matplotlib, plotly, xgboost)
- Jupyter Notebook

## 🤖 AI Support
We used ChatGPT to debug code, manage our timeline, and help organize key deliverables.

## 📁 Files in This Repository
- `HepatitisC_Predictive_Model.ipynb` – Main notebook with code
- `HepatitisCdata.csv` – Dataset used
- `presentation.pdf` – Final project presentation
- `README.md` – Project overview
