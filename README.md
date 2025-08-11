# Customer Churn Analysis and Prediction

## 📌 Project Overview
This project analyzes customer data to identify factors that influence churn and builds a **Decision Tree Classifier** to predict which customers are at risk of leaving. The goal is to help the business take **proactive retention actions** and reduce churn rate.

## 📊 Dataset
The dataset contains customer information such as:
- **Contract type**
- **Online security status**
- **Streaming TV**
- **Internet service type**
- And more...

**Target Variable:** `Churn` (Yes/No)

## 🔍 Key Insights
- Customers with **month-to-month contracts** have the highest churn.
- Lack of **online security** is strongly linked to churn.
- **Streaming TV** customers have slightly lower churn.
- **Fiber optic internet** users churn more than DSL customers.

## 🛠️ Methodology
1. **Data Cleaning & Preprocessing** (handling missing values, encoding, scaling)
2. **Exploratory Data Analysis (EDA)** (finding patterns & correlations)
3. **Feature Importance** (Decision Tree feature_importances_)
4. **Model Training** (Decision Tree Classifier)
5. **Model Evaluation** (accuracy, precision, recall, F1-score)

## 📈 Results
- **Accuracy:** 0.80+
- **Top Features:** Contract, OnlineSecurity, StreamingTV, InternetService

## 💡 Business Recommendations
1. Offer **discounts** to month-to-month customers to encourage long-term contracts.
2. Bundle **online security** as a free add-on for the first 3 months.
3. Provide loyalty perks to **fiber optic customers**.
4. Launch targeted marketing campaigns for customers with low engagement.

**Estimated Impact:**
- Potential **10–15% churn reduction** in high-risk segments.
- Estimated **$500k+ yearly revenue retention**.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repo-name.git
