# 📊 Data Warehouse ETL and Visualization Project

This project implements an ETL pipeline and generates meaningful visualizations based on a star schema data warehouse. The data is extracted from an operational database, transformed into dimensional format, and loaded into a MySQL database.
## 🧱 Star Schema Design

- **Fact Tables**:
  - `fact_daily_inventory`: Inventory quantities by day
  - `fact_monthly_payment`: Payments by month

- **Dimension Tables**:
  - `dim_date`
  - `dim_staff`
  - `dim_film`
  - `dim_store`
  - `dim_rent`

## 🔄 ETL Process

- Extracts raw data from source
- Removes duplicates, handles nulls
- Maps and validates foreign keys
- Loads data into dimensional model
