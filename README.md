# SQLite-Database-Using-Python

##  Objective
Use Python and SQLite to extract and visualize simple sales data. This project demonstrates how to:
- Query a local SQLite database using SQL
- Load results into a pandas DataFrame
- Display a sales summary using print and a bar chart via matplotlib

##  Tools & Libraries Used
- **Python** (Built-in `sqlite3`)
- **pandas** for data handling
- **matplotlib** for visualization
- **SQLite** as a lightweight local database

##  What the Code Does
1. Creates (or connects to) `sales_data.db`
2. Creates a `sales` table and inserts sample records
3. Runs a SQL query to calculate:
   - Total quantity sold per product
   - Total revenue per product
4. Loads the result into a DataFrame
5. Prints the summary
6. Visualizes revenue by product as a bar chart
