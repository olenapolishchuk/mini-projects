# sales-dashboard

This project explores and analyzes fictional sales data to generate insights using Python and visualization tools.

## Project Structure

- `data/raw_sales_data.csv`: The original raw dataset containing missing values, duplicates, and inconsistent entries.
- `data/cleaned_sales_data.csv`, `data/cleaned_sales_data.xlsx`: The cleaned datasets .
- `notebooks/cleaning_and_eda.ipynb`: Jupyter notebook that cleans the data and performs exploratory analysis.
- `visuals/`: Folder for visualizations .
- `reports/`: Optional business report summaries.

## Goals

- Identify and fix data quality issues (missing values, duplicates, incorrect formats).
- Explore sales patterns by region and product.
- Generate key business insights with visualizations.
- Export results to Excel and PDF
- Build a professional dashboard in Power BI


## Tools Used

- Python (pandas,numpy, matplotlib, seaborn, reportlab)
- Excel (via pandas export)
- Power BI for interactive dashboard
- Jupyter Notebook (for development)


## Key Analysis Steps

1. **Data Cleaning**:
    - Remove or fill missing values
    - Strip columns, drop duplicates
    - Convert types, create new metrics
2. **EDA**:
    - Total revenue by region
    - Sales trends by product
    - Visualizations and summaries
3. **Core KPIs**:
    - Total Revenue
    - Units Sold
    - Average Order Value
    - Revenue per Unit

##  Dashboard
Interactive Power BI dashboard includes:
- Revenue by Region / Category
- Trend over Time
- KPIs Cards
- Slicers by Region, Category, Month

## How to Run

1. Clone the repository
2. Place `raw_sales_data.csv` inside `data/` folder
3. Run `notebooks/cleaning_and_eda.ipynb` using Jupyter

---

## License

This project is licensed under the [MIT License](LICENSE).



