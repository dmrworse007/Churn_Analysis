# Customer Churn Prediction & Analytics

## Overview

Customer churn significantly impacts revenue and long-term business growth. This project focuses on analyzing customer behavior, identifying churn patterns, and predicting customers likely to discontinue a service using machine learning techniques. The solution combines data analytics, SQL-based business intelligence, predictive modeling, and interactive Power BI dashboards to support customer retention strategies.

---

## Features

- Comprehensive customer churn analysis
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- SQL-based business insights generation
- Churn prediction using Random Forest Classifier
- Interactive Power BI dashboard
- Business-focused recommendations for retention

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- SQL
- Power BI
- Jupyter Notebook

---

## Dataset Attributes

The dataset contains customer information such as:

- Customer ID
- Gender
- Senior Citizen Status
- Partner and Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming Services
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

---

## Project Workflow

### 1. Data Collection and Preparation

- Imported customer churn dataset
- Handled missing and inconsistent values
- Encoded categorical variables
- Performed feature scaling and transformation
- Created machine-learning-ready dataset

### 2. Exploratory Data Analysis

- Churn distribution analysis
- Customer segmentation
- Correlation analysis
- Service-wise churn patterns
- Tenure and revenue analysis
- Contract-type impact analysis

### 3. SQL Analytics

Business insights generated using SQL queries:

- Customer churn trends
- Revenue loss estimation
- Contract-wise churn analysis
- Service adoption patterns
- Customer retention metrics

### 4. Machine Learning Model

Implemented a Random Forest Classifier to predict customer churn.

#### Pipeline

- Train-Test Split
- Feature Engineering
- Model Training
- Prediction
- Performance Evaluation

#### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score

### 5. Power BI Dashboard

Interactive dashboard containing:

- Churn Overview
- Customer Demographics
- Revenue Analysis
- Service Usage Insights
- Retention KPIs
- Customer Segmentation Visualizations

---

## Repository Structure

```text
Customer-Churn-Prediction/
│
├── Random_Forest_Codes.ipynb
├── Churn_Analysis_visualization.pbix
├── SQLQuery1.sql
├── SQLQuery2.sql
├── SQLQuery3.sql
├── SQLQuery4.sql
├── SQLQuery5.sql
├── README.md
```

---

## Key Business Insights

- Customers on month-to-month contracts exhibit higher churn rates.
- Lower-tenure customers are more likely to discontinue services.
- Long-term contracts improve retention.
- Customers using multiple services demonstrate greater loyalty.
- Contract type, tenure, and monthly charges are among the strongest churn indicators.

---

## Machine Learning Results

The Random Forest model effectively identifies customers at risk of churn, enabling organizations to take proactive retention measures and reduce customer attrition.

---

## Applications

- Customer Retention Strategy
- Revenue Protection
- Customer Risk Assessment
- Marketing Campaign Optimization
- Subscription Business Analytics

---

## Future Enhancements

- XGBoost and LightGBM implementation
- Hyperparameter tuning with GridSearchCV
- Real-time churn prediction API
- Flask/FastAPI deployment
- Automated dashboard refresh pipeline
- Cloud deployment using AWS or Azure

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/dmrworse007/Churn_Analysis.git
cd Churn_Analysis
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
Random_Forest_Codes.ipynb
```

Run all cells to reproduce analysis and model training.

---

## Project Highlights

- End-to-end Data Analytics workflow
- SQL-based business intelligence
- Machine Learning prediction pipeline
- Interactive Power BI dashboard
- Actionable customer retention insights

---

## Author

**Dibya Pratim Kashyap**  
B.Tech, Computer Science and Engineering  
Indian Institute of Technology Guwahati

GitHub: https://github.com/dmrworse007
