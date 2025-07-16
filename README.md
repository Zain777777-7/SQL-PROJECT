# 📚 SQL Project: Online Bookstore Data Exploration

## 🧠 Project Summary

This SQL project dives deep into the operations of a fictional online bookstore by analyzing its transactional and customer data. The goal is to **apply core SQL concepts**—from simple data retrieval to complex aggregation and joins—by answering real-world business questions.

> ✅ Whether you're an aspiring data analyst, a student learning SQL, or preparing for data interviews, this project is a practical example of data exploration using **relational databases**.

---

## 📦 Dataset Description

This project is based on **three interconnected datasets**, stored in CSV format, simulating the everyday data of an online bookstore.

### 📘 Books.csv
- `Book_ID`: Unique identifier for each book  
- `Title`: Name of the book  
- `Author`: Author’s name  
- `Genre`: Genre/category of the book  
- `Published_Year`: Year the book was published  
- `Price`: Price of the book  
- `Stock`: Available stock

### 👤 Customers.csv
- `Customer_ID`: Unique identifier for each customer  
- `Name`: Full name  
- `Email`: Contact email  
- `Phone`: Contact number  
- `City`: City of residence  
- `Country`: Country of residence

### 🛒 Orders.csv
- `Order_ID`: Unique identifier for each order  
- `Customer_ID`: Foreign key to Customers  
- `Book_ID`: Foreign key to Books  
- `Order_Date`: Date of order  
- `Quantity`: Number of books ordered  
- `Total_Amount`: Total price for the order

---

## 🔍 SQL Topics Covered

### ✅ Basic Queries

1. **Filter by Genre** – Retrieve all books in the "Fiction" genre  
2. **Year Filter** – Find books published after 1950  
3. **Location Filter** – List all customers from Canada  
4. **Date Range** – Show orders placed in November 2023  
5. **Stock Count** – Calculate total stock available  
6. **Max Value** – Get details of the most expensive book  
7. **Order Quantity Filter** – Customers who ordered more than one copy  
8. **Price Filter** – Orders with total amount exceeding $20  
9. **Genre List** – List all unique genres  
10. **Min Stock** – Book with the lowest stock  
11. **Total Revenue** – Sum of all order amounts  
12. **Books by Author** – Retrieve books by a specific author  

### 🔬 Advanced Queries

1. 📊 Total number of books sold per genre  
2. 💰 Average price of Fantasy books  
3. 🧾 Customers with at least 2 orders  
4. 🏆 Most frequently ordered book  
5. 🎯 Top 3 most expensive Fantasy books  
6. ✍️ Total quantity of books sold by author  
7. 📍 Cities of customers who spent over $30  
8. 💸 Customer who spent the most  
9. 📉 Stock remaining after fulfilling orders  
10. 📚 Total revenue per genre  
11. 🧑‍🤝‍🧑 Customers who bought books by a specific author  
12. ❌ Books never ordered  
13. 📊 Average order value per customer  
14. 📈 Rank books by quantity sold  
15. 📅 Monthly sales revenue

---

## 🚀 Skills Demonstrated

- SQL Joins (INNER, LEFT)
- Aggregations with `SUM()`, `AVG()`, `COUNT()`
- `GROUP BY`, `HAVING`, and `DISTINCT`
- Date filtering and formatting
- Subqueries and ordering
- Ranking and limiting results

---

## 💡 Key Highlights

- Hands-on with **realistic business queries**
- Demonstrates ability to handle **relational data models**
- Prepares for data roles in **e-commerce, retail, and BI**
- All queries written in **standard ANSI SQL**

---

## 🌟 Final Thoughts

This project is more than just SQL practice—it's a step toward becoming a **data storyteller**. With real-world scenarios and insightful queries, you're not just learning SQL, you're **thinking analytically** like a data professional.

---

## 🔗 Connect With Me


- LinkedIn: https://www.linkedin.com/in/zain-shaukat4228/


---

> ✨ Thank you for exploring! Feel free to fork this project or reach out if you'd like to collaborate.

