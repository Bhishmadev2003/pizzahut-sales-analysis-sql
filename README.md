# 🍕 pizzahut-sales-analysis-sql

This project focuses on analyzing **PizzaHut's sales data using SQL**. It includes a series of SQL queries to extract meaningful business insights from the raw dataset — helping understand revenue trends, customer preferences, and product performance.

---

## 🎯 Project Objective

To perform end-to-end **exploratory data analysis** using SQL to answer key business questions such as:

- Which pizzas generate the most revenue?  
- What is the average order value by category or size?  
- When do most customers place their orders?  
- Which categories or sizes are most preferred?

---

## 🛠️ Tools & Technologies

- **SQL** (MySQL)  
- **DBMS** – Workbench  
- **Excel** – Initial data view & validation

---

## 📌 Key SQL Analyses

- 🔝 Top 5 best-selling pizzas  
- 💰 Total revenue by category and pizza size  
- 📆 Monthly & weekly sales trends  
- 🕒 Peak ordering hours  
- 📦 Order count by pizza type

---

## 🔍 Sample Query

```sql
SELECT pizza_name, SUM(total_price) AS revenue
FROM pizzahut_sales
GROUP BY pizza_name
ORDER BY revenue DESC
LIMIT 5;
```

---

## 🌱 Learning Outcomes

- Practiced SQL joins, aggregation, filtering, and window functions  
- Translated business questions into analytical SQL queries  
- Improved understanding of retail/F&B data structure  
- Prepared for real-world SQL case interviews

---

## 🔗 View Project

👉 [**View on GitHub**](https://github.com/Bhishmadev2003/pizzahut-sales-analysis-sql)

---

## 📬 Connect with Me

**Bhishmadev Naskar**  
📧 [LinkedIn](https://www.linkedin.com/in/bhishmadevnaskar/)
