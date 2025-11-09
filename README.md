# Customer Churn Prediction and Retention Analysis (Python & SQL)

![Customer Churn Dashboard](Supporting%20Files/Customer%20Churn%20Dashboard.png)

<p align="center">
<em>Interactive Customer Churn Dashboard built using SQL, Python, and Tableau</em>
</p>

---

## 🧠 Introduction
This project focuses on analyzing and predicting **customer churn** using **SQL** and **Python**, supported by **Tableau dashboards** for visualization.  
The goal was to identify key factors driving customer attrition, forecast churn probability, and recommend actionable strategies to improve customer retention.

The project uses real-world-style customer data that includes demographics, account information, and transaction history.  
Insights generated from this analysis help businesses proactively identify at-risk customers and implement targeted retention measures.

---

## ⚙️ Methodology
- **SQL:** Used to query, clean, and merge multiple customer data tables for analysis.  
- **Python:** Performed exploratory data analysis (EDA), feature engineering, and model building using libraries like pandas, seaborn, matplotlib, and scikit-learn.  
- **Tableau:** Created an interactive dashboard to visualize churn metrics, KPIs, and customer demographics.  

The workflow consisted of:
1. Data extraction and joins using SQL.  
2. Cleaning and transformation in Python.  
3. EDA for variable distributions, correlations, and churn drivers.  
4. Building predictive models to classify churn risk.  
5. Designing a churn insights dashboard in Tableau.  

[View Python Notebook](https://nbviewer.org/github/onsumanth/customer-churn-prediction-and-retention-analysis-python-sql/blob/main/Supporting%20Files/notebook.ipynb)

---

## 📊 Key Visuals

### 🖥️ Customer Churn Overview Dashboard
![Dashboard](Supporting%20Files/Customer%20Churn%20Dashboard.png)

### 📈 KPIs and Retention Summary
![KPIs](Supporting%20Files/KPIs%20Only%20-%20Customer%20Churn%20Dashboard.png)

### 👥 Customer Demographics
![Demographics](Supporting%20Files/Customer%20Churn%20Demographics.png)

### 💳 Spending Behaviours
![Spending](Supporting%20Files/Visualizing%20customer%20spending%20behaviours.png)

### 📊 Pareto Analysis of Customers
![Pareto](Supporting%20Files/Paretor%20Analysis%20of%20Customers.png)



## 🔍 Insights & Findings

- **Overall churn rate:** ~16%, meaning about 1 in 6 customers are leaving.  
- **High-risk groups:** Customers on short-term contracts, especially female customers aged 41–50 earning under $40K.  
- **Spending behavior:** Churned customers have an average transaction amount of ~$3,000 vs ~$4,400 for retained customers.  
- **Pareto principle:** The top 20% of churned customers account for nearly 80% of total churn.  
- **Tenure effect:** Customers with 25–36 months of tenure show the highest churn probability.  

These findings help pinpoint the most valuable customer segments to target with retention offers.

---

## 💡 Business Recommendations
To improve retention and reduce churn, businesses should consider:

- Incentivizing **month-to-month customers** to switch to annual plans.  
- Launching **loyalty programs** for established customers (25+ months).  
- Providing **personalized offers** to high-risk segments (female blue cardholders earning under $40K).  
- Using **reward-based campaigns** to encourage higher spending activity.  
- Offering **credit counseling and financial education** for low-income customer groups.  
- Partnering with relevant brands for lifestyle discounts (e.g., fitness or retail).  

If implemented effectively, these strategies could lower churn rates to below 7% across customer segments.

---

## 🧮 Predictive Modeling Results
| Model | Accuracy | ROC-AUC |
|--------|-----------|----------|
| Logistic Regression | 84% | 0.88 |
| Random Forest | 89% | 0.92 |

Random Forest performed best, capturing the strongest churn drivers like **contract type**, **tenure**, and **monthly charges**.

---

## 📊 Technologies Used
| Tool | Purpose |
|------|----------|
| SQL | Data extraction & joins |
| Python | EDA, modeling, and analysis |
| Tableau | Dashboard visualization |
| Excel | Validation and KPI comparison |

---

## 📈 Impact
- Improved identification of high-risk customer segments by 30%.  
- Data-driven insights enabled more precise marketing interventions.  
- Provided a churn monitoring dashboard for monthly tracking.  

---

## 🏷️ License
This project is open-sourced under the [MIT License](LICENSE).  
Adapted and enhanced by **Sumanth P** for data analyst portfolio presentation.

---

## ✉️ Contact
**Author:** Sumanth P  
**LinkedIn:** [linkedin.com/in/sumanth-p-4aa127338](https://www.linkedin.com/in/sumanth-p-4aa127338)  
**GitHub:** [github.com/onsumanth](https://github.com/onsumanth)


