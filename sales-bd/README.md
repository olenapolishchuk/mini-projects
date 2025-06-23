# sales-bd
A realistic sales reporting project using SQL and relational databases. Includes full schema design, data population, analytical queries, and  BI dashboard.
---

## 📁 Files

- `combined_sales_report.csv`, – combined export of all metrics
- `sales_bd.pbix` – the Power BI dashboard (included separately)
- `insert_data.sql`, `create_tables.sql` – SQL version (optional)
- `queries_postgresql.sql` – professional PostgreSQL queries for insights

---

# 📊 Sales Analytics Dashboard (Power BI)

This project showcases a  **sales analytics report** built in **Power BI** using pre-processed CSV files.

It covers key business insights and KPIs such as:
- ✅ Total Revenue
- ✅ Average Order Value
- ✅ Revenue by Region
- ✅ Monthly Revenue Trends
- ✅ Top Customers by Lifetime Value
- ✅ Top Selling Products
- ✅ 3-Month Rolling Average Revenue

---

## 📦 Tech Stack

- **Power BI Desktop**
- **PostgreSQL** 
- CSV-based data model for easy portability

---

## 💾 Database Setup

- **Database system:** PostgreSQL
- **Schema & data setup:** provided via `create_tables.sql` and `insert_data.sql`
- **SQL queries:** written in `queries_postgresql.sql` — optimized for PostgreSQL dialect
   
---


### ▶️ How to Reproduce

1. Install [PostgreSQL](https://www.postgresql.org/)
2. Create a new database (e.g., `sales_db`)
3. Run `create_tables.sql` to define schema
4. Run `insert_data.sql` to populate data
5. Use `queries_postgresql.sql` for analysis and KPIs
6. Open `report.pbix` in Power BI to connect to the database and view dashboard

> ⚠️ You may need to update the data source in Power BI to match your local PostgreSQL connection.

---

## 🧑‍💼 Author

Built as part of a Data Analytics Portfolio. Perfect for showcasing skills in:

- Data visualization
- Business intelligence
- SQL + BI integration

---

## License

This project is licensed under the [MIT License](LICENSE).

