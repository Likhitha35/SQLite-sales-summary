# SQLite-sales-summary
Analyzing a simple sales dataset using SQLite, SQL queries in Python, and visualizing results with matplotlib.


# Task 7: Basic Sales Summary using SQLite and Python

## 📌 Objective
Analyze a small sales dataset using SQL queries in Python (via sqlite3), summarize sales by product, and visualize the results with a bar chart.

## 🛠 Tools Used
- Python
- SQLite (`sqlite3` module)
- pandas
- matplotlib
- Jupyter Notebook

## 🧩 Task Steps
1. Created a SQLite database (`sales_data.db`) with a `sales` table.
2. Inserted sample sales data including product names, quantities, and prices.
3. Ran an SQL query to calculate:
   - Total quantity sold per product.
   - Total revenue per product (`quantity × price`).
4. Loaded the SQL result into a pandas DataFrame.
5. Printed the results using `print()`.
6. Visualized total revenue by product using a bar chart via matplotlib.

## 📊 Output
The chart displays total revenue per product. Top-selling products by revenue include:
- **Milk**
- **Juice**
- **Apples**

Products with the least revenue include:
- **Eggs**
- **Bananas**

The bar chart helps quickly compare sales performance across products.



🔗 Submission This repository contains:
- `sql.ipynb` – Jupyter Notebook with complete task code.
- `Bar Chart.png` – Bar chart screenshot.
- `README.md` – This file.

---
