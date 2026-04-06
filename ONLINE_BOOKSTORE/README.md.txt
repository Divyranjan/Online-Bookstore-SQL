# 📚 Online Bookstore Data Analysis (SQL Project)

## 📌 Overview
This project demonstrates SQL skills by analyzing an online bookstore dataset.  
It covers database creation, data import from CSV files, and solving real-world business queries using SQL.

---

## 🛠️ Tech Stack
- 💻 MySQL Workbench
- 📁 CSV Files (Books, Customers, Orders)
- 🧠 SQL (Joins, Aggregations, Window Functions)

---

## 🗂️ Database Schema

### 📘 Books
- Book_ID (PK)
- Title
- Author
- Genre
- Published_Year
- Price
- Stock

### 👤 Customers
- Customer_ID (PK)
- Name
- Email
- Phone
- City
- Country

### 🛒 Orders
- Order_ID (PK)
- Customer_ID (FK)
- Book_ID (FK)
- Order_Date
- Quantity
- Total_Amount

---

## 📊 Key SQL Concepts Used
- ✅ Data Import using `LOAD DATA INFILE`
- ✅ Filtering using `WHERE`
- ✅ Aggregations (`SUM`, `AVG`, `COUNT`)
- ✅ Joins (`INNER JOIN`, `LEFT JOIN`)
- ✅ Window Functions (`DENSE_RANK`)
- ✅ Grouping (`GROUP BY`, `HAVING`)
- ✅ NULL handling (`COALESCE`)

---

## 📈 Business Questions Solved

### 🔹 Basic Analysis
- Retrieve all Fiction books  
- Find books published after 1950  
- List customers from Canada  
- Find orders in a specific month  
- Calculate total stock  

### 🔹 Intermediate Analysis
- Find most expensive book  
- Find least stocked book  
- List unique genres  
- Calculate total revenue  

### 🔹 Advanced Analysis
- Total quantity sold per genre  
- Average price of Fantasy books  
- Customers with multiple orders  
- Most frequently ordered book  
- Top 3 expensive Fantasy books  
- Total books sold per author  
- Orders above certain value with customer location  
- Top spending customer  
- Remaining stock after fulfilling orders  

---

## 🚀 Key Insights

- 📊 Identified best-selling books using ranking functions  
- 💰 Calculated total revenue generated from orders  
- 👥 Found high-value customers based on spending  
- 📦 Tracked inventory and remaining stock dynamically  
- 📚 Analyzed genre and author performance  

---

## 📁 Project Structure

```
📦 Online-Bookstore-SQL
 ┣ 📜 online_bookstore_analysis.sql
 ┣ 📜 Books.csv
 ┣ 📜 Customers.csv
 ┣ 📜 Orders.csv
 ┗ 📜 README.md
```

---

## 💡 How to Run

1. Open MySQL Workbench  
2. Create a new schema (database)  
3. Run the SQL file:  
   ```
   online_bookstore_analysis.sql
   ```
4. Ensure CSV files are placed in:
   ```
   C:/ProgramData/MySQL/MySQL Server 8.0/Uploads/
   ```

---

## 🎯 Learning Outcomes

- Strengthened SQL fundamentals  
- Learned real-world data analysis using SQL  
- Understood joins, aggregations, and window functions deeply  
- Built a portfolio-ready project  

---

## 🔥 Author

**Divyranjan Routray**  
- Aspiring Software Developer 💻  
- Skilled in SQL, Frontend Development, and DSA  

---

## ⭐ If you like this project
Give it a ⭐ on GitHub!