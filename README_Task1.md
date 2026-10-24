#  Sales Data Analysis

## Project Overview
Analyze sales transactions to calculate business metrics, compare category and product performance, examine monthly and quarterly trends, and visualize geographic sales distribution.

## Objectives
- Calculate gross revenue, discounts, net sales, product cost, profit, profit margin, Average Order Value (AOV), and units sold.
- Analyze monthly, quarterly, and exploratory month-of-year sales patterns.
- Identify top-selling products/categories and products with the highest profit margins.
- Compare sales across regions and sales channels.
- Validate financial totals and communicate evidence-based insights.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## Dataset
Place `Copy of codenova_sales_sample.csv` in the same folder as the notebook. If you rename the dataset, update the dataset-loading path in the notebook.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install packages if needed: `pip install pandas numpy matplotlib seaborn jupyter`.
3. Keep the notebook and CSV in the same folder.
4. Open `Sales_Data_Analysis_Task1_Improved.ipynb`.
5. Select **Kernel → Restart Kernel and Run All Cells**.
6. The notebook saves chart images in a `charts/` directory at 300 DPI.

## Outputs
- Key business metrics and financial reconciliation checks.
- Category and product sales/profit summaries.
- High-margin product ranking and chart.
- Monthly and quarterly trend charts.
- Calendar-month comparison and year-month trend.
- Regional and sales-channel comparisons.
- Data-generated business insights and strategic recommendations.

## Interpretation Notes
Profit margin is different from total profit: a high-margin product may contribute less total profit if its sales volume is low. The available dataset covers less than two complete years, so calendar-month comparisons are exploratory and cannot establish a reliable recurring seasonal pattern.

## Business Recommendations
- Monitor stock and demand for top-selling products.
- Evaluate high-margin products for promotions or bundles without eroding margins.
- Investigate lower-performing regions and categories before reallocating marketing spend.
- Compare profit as well as sales when evaluating sales channels.
- Continue collecting data before making strong seasonal or forecasting claims.
