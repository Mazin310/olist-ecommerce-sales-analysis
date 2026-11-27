# Olist E-commerce Sales Analysis

Power BI report analyzing the Brazilian Olist e-commerce public dataset.

## Download the report
The full report (`olist-ecommerce-sales-analysis.pbix`) is in [Releases](../../releases), split into 2 parts (`.pbix.001` and `.pbix.002`) because of GitHub's upload size limit.

To rebuild it:
1. Download both parts into the same folder
2. Join them, either:
   - Windows Command Prompt: `copy /b olist-ecommerce-sales-analysis.pbix.001+olist-ecommerce-sales-analysis.pbix.002 olist-ecommerce-sales-analysis.pbix`
   - or open the `.001` file with 7-Zip and extract
3. Open `olist-ecommerce-sales-analysis.pbix` in Power BI Desktop

## Report pages
- **Home** — navigation / overview
- **Sales & Orders** — revenue, orders, delivery performance
- **Products & Sellers** — category and seller analysis
- **Customer & Reviews** — customer behavior and satisfaction

## Data model
Built on the Olist public datasets: orders, order items, order payments, order reviews, customers, sellers. Includes a `_Measures` table with 50 DAX measures (sales, freight, orders, delivery, customers, products, payments, reviews, YoY/MoM time intelligence) and a `Dim_Date` calendar table.

## Tools
- Microsoft Power BI Desktop (enhanced report format, PBIR)
