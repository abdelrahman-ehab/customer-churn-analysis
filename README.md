# Customer Churn Analysis & Prediction

## 📌 Overview
This project analyzes customer churn data to uncover trends and predict customer attrition using a machine learning model. The workflow spans **SQL data processing**, **Power BI visualization**, and **Random Forest classification**. Key insights are delivered through an interactive dashboard, and the model predicts churn with actionable accuracy.

---

## 📂 Project Workflow
1. **Data Ingestion**:  
   - Source: CSV file → Ingested into SQL Server.  
   - Cleaned null values and performed aggregations/summaries in SQL.  
   - Created SQL views for structured access.

2. **Power BI Dashboard**:  
   - Connected to SQL Server views.  
   - Built interactive reports focusing on:  
     - **Demographics**: Age, gender, tenure.  
     - **Geography**: Regional churn trends.  
     - **Account & Contract**: Payment methods, contract types.  
     - **Service Analysis**: Internet/phone service preferences.  

3. **Machine Learning**:  
   - Trained a Random Forest classifier to predict churn.  
   - Addressed class imbalance with SMOTE oversampling.  
   - Achieved **84% accuracy** with detailed confusion matrix analysis.

---

## 🛠️ Features
### Power BI Dashboard
- **Demographic Insights**: Customer distribution by age, gender, and tenure.  
- **Geographic Heatmaps**: Churn rates by region.  
- **Contract & Service Analysis**: Trends in contract types (monthly vs. annual) and service bundles.  
- **Churn Predictors**: Highlighted key drivers of churn (e.g., payment delays, service complaints).

### Machine Learning Model
- **Algorithm**: Random Forest Classifier.  
- **Key Metrics**:  
  - Precision: 72% (Churn), 88% (Non-Churn)  
  - Recall: 69% (Churn), 89% (Non-Churn)  
  - F1-Score: 71% (Churn), 88% (Non-Churn)  
- **Class Imbalance Handling**: SMOTE oversampling.

---

## 🚀 Installation & Usage
### Prerequisites
- SQL Server (for data processing).  
- Power BI Desktop (for visualization).  
- Python 3.8+ with libraries:  
  ```bash
  pandas, numpy, scikit-learn, imbalanced-learn, pyodbc, matplotlib
