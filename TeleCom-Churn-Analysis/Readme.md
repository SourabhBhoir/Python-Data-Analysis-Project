# 📊 Customer Churn Analysis (Python + ML Project)

## 📌 Project Overview

This project focuses on analyzing customer churn behavior using Python.
The goal is to identify key factors that lead to customer churn and provide actionable insights to improve customer retention.

Instead of using a common dataset, a custom dataset of 5000+ customer records was generated using Python with realistic business logic.

---

## 🎯 Objective

* Understand customer churn patterns
* Perform data cleaning and preprocessing
* Conduct exploratory data analysis (EDA)
* Build a machine learning model to predict churn
* Generate business insights

---

## 📂 Dataset Information

* Total Records: 5000+
* Features:

  * CustomerID
  * Gender
  * SeniorCitizen
  * Tenure
  * MonthlyCharges
  * TotalCharges
  * Contract
  * PaymentMethod
  * Churn (Target Variable)

### 🔹 Dataset Creation

The dataset was synthetically generated using Python with conditions such as:

* Customers with high monthly charges and monthly contracts are more likely to churn
* Customers with low tenure have higher churn probability
* Long-term contract customers have lower churn

---

## 🧹 Data Cleaning & Preprocessing

* Handled missing values
* Converted data types (TotalCharges)
* Encoded categorical variables
* Created new features:

  * AvgCharges (TotalCharges / Tenure)
  * IsSenior

---

## 📊 Exploratory Data Analysis (EDA)

Performed analysis using Pandas, Matplotlib, and Seaborn.

### Key Analysis:

* Churn distribution
* Churn rate by contract type
* Monthly charges vs churn
* Tenure vs churn

---

## 🤖 Machine Learning Model

* Model Used: Logistic Regression
* Train-Test Split: 80-20
* Accuracy achieved: ~ (update after running your model)

---

## 📈 Key Insights

* Customers with **month-to-month contracts** have higher churn rates
* Customers with **higher monthly charges** are more likely to churn
* Customers with **short tenure** show higher churn behavior
* Long-term contracts significantly reduce churn

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
customer-churn-python/
│
├── data/
├── notebook/
├── src/
├── outputs/
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook or Python script

---

## 💡 Future Improvements

* Add advanced ML models (Random Forest, XGBoost)
* Deploy model using Flask or Streamlit
* Build interactive dashboard (Power BI / Tableau)

---

## 👨‍💻 Author

Sourabh Bhoir

---

## ⭐ Conclusion

This project demonstrates end-to-end data analysis including data generation, cleaning, visualization, and predictive modeling. It highlights how data-driven insights can help businesses reduce customer churn.

