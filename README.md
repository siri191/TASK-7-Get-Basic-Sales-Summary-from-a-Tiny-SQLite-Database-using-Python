# TASK-7-Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python
# Task 7: Basic Sales Summary from SQLite Database using Python

## 📌 Objective
Use **SQL inside Python** to pull simple sales information (total quantity sold, total revenue) and display it using:
- Basic `print()` statements
- A simple **Matplotlib** bar chart

---

## 🛠 Tools Used
- Python 3.x
- SQLite (`sqlite3` module – built into Python)
- Pandas
- Matplotlib
- Jupyter Notebook or Python script (`.py`)

---

## 📂 Dataset
A small SQLite database file: **`sales_data.db`**  
Contains **one table**: `sales`

**Table Structure**:
| Column  | Type   | Description                |
|---------|--------|----------------------------|
| id      | INT    | Primary Key (Auto)          |
| date    | TEXT   | Date of sale                |
| product | TEXT   | Product name                |
| quantity| INT    | Quantity sold               |
| price   | REAL   | Price per unit               |

---

🔹 Features:

1.Automatic Data Creation: Generates 100 random sales records with product names, quantities, prices, and sale dates.

2.SQL Inside Python: Uses standard SQL queries within Python scripts for data aggregation and summarization.

3.Pandas Integration: Displays query results in clean, formatted DataFrames.

4.Data Visualization: Produces professional charts to aid business decision-making.

5.Self-Contained Workflow: No internet or external database setup required — works offline using only Python’s built-in SQLite.

💡 Learning Outcomes:

1.Understand how to connect Python to SQLite databases.

2.Learn to write and run SQL queries inside Python.

3.Practice data aggregation and grouping using SQL GROUP BY.

4.Explore data visualization techniques with Matplotlib.

5.Gain experience in building automated, end-to-end analysis scripts.




