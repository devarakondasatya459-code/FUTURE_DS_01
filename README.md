# FUTURE_DS_01: Sales Analysis

## Objective
Analyze sales data to calculate key business KPIs, understand revenue trends, and identify top-performing products, categories, and regions.

## Dataset
The dataset is located in `data/sales_data.csv` and includes the following columns:
- `Order ID` – Unique order identifier
- `Order Date` – Date of the order
- `Product Name` – Name of the product sold
- `Category` – Product category
- `Quantity` – Quantity sold
- `Sales` – Total sales value
- `Profit` – Profit for the order
- `Region` – Region of the sale

## Steps Taken
1. Load and clean the dataset (convert dates, remove duplicates, handle missing values)
2. Calculate business KPIs:
   - Total Revenue
   - Total Profit
   - Total Orders
   - Total Quantity Sold
   - Average Order Value
3. Perform trend analysis:
   - Monthly revenue trends
   - Top 10 selling products
   - Category performance
   - Regional sales performance
4. Visualize insights using charts
5. Export a summary CSV report to `outputs/sales_summary_report.csv`

## Tools & Libraries
- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`

## How to Run
```bash
python scripts/sales_analysis.py
