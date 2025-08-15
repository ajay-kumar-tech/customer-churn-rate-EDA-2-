# Customer Churn Rate Analysis

## 📌 Overview
This project analyzes customer churn data to understand customer retention patterns and identify improvement opportunities.  
It includes **Exploratory Data Analysis (EDA)**, churn visualization by demographics, and an **interactive geographical churn map**.

## 🚀 Features
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA) on customer profiles  
- Churn distribution by age, geography, products, and account balance  
- Interactive world map with:  
  - **Circle size** = number of customers  
  - **Circle color** = churn rate (Green = Low, Red = High)  
- Insights for improving customer retention  

## 🛠 Tech Stack
- Python  
- Pandas, NumPy – Data handling  
- Matplotlib, Seaborn – Data visualization  
- Folium – Interactive maps  
- Geopy – Country geocoding  

## 📂 Dataset Description
| Column | Description |
|--------|-------------|
| CustomerId | Unique ID for each customer |
| Surname | Customer’s last name |
| CreditScore | Credit score of the customer |
| Geography | Country of the customer |
| Gender | Male / Female |
| Age | Age of the customer |
| Tenure | Years with the bank |
| Balance | Account balance |
| NumOfProducts | Number of bank products used |
| HasCrCard | 1 = Has credit card, 0 = No credit card |
| IsActiveMember | 1 = Active customer, 0 = Inactive |
| EstimatedSalary | Estimated annual salary |
| Exited | 1 = Churned, 0 = Retained |

## 📊 How to Run
1. Clone the repository  
```bash
git clone <repo-url>
cd <repo-folder>
