# E-commerce Analytics Dashboard

A customer analysis project built using **Python, PostgreSQL, and Microsoft Power BI**. The project explores customer distribution, spending behaviour, preferred product categories, customer segments, and country-level revenue.

> **Portfolio note:** The raw CSV dataset is not included in this repository. This keeps the repository focused on the analysis work and avoids publishing the source data.

## Project Overview

This project follows an end-to-end data analytics workflow:

1. Inspect and clean customer data using Python.
2. Store and analyse the data with PostgreSQL.
3. Answer business questions using SQL.
4. Build an interactive Power BI dashboard.
5. Summarise findings and provide business recommendations.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data loading, inspection, cleaning, and preparation |
| Pandas and NumPy | Data manipulation |
| Jupyter Notebook | Documenting the Python workflow |
| PostgreSQL | Data storage and SQL analysis |
| Microsoft Power BI | Interactive dashboard and visualisation |

## Dataset Overview

The analysis dataset contains **950 customer records and 10 columns** after duplicate removal. Each row represents one customer.

Key fields include:

- 
- 
- 
- 
- 
- 
- 
- 
- 
- 

The report records 52 country values, including an  category.

## Project Structure



Add only the files that you actually have. The SQL script and Power BI  file should be placed in their folders before you publish the repository. The CSV dataset is intentionally excluded.

## Key Analysis Results

The figures below are reported for the 950-row analysis dataset:

| Metric | Result |
|---|---:|
| Total customers | 950 |
| Total spending | 7,933.17 |
| Average spending per customer | 03.09 |
| Customers with zero spending | 692 (72.8%) |
| Customers with spending above zero | 258 (27.2%) |
| Customers above average spending | 228 |
| Countries, including  | 52 |

### Key Business Insights

- Spending is concentrated among a relatively small group of customers.
- The top 95 customers (10% of the customer base) account for approximately 71% of total spending.
- Regular and Premium customer segments together account for approximately 88% of total spending.
- The 571 customers labelled  have zero recorded spending in this dataset.
- Premium customers represent a small share of customers but contribute a substantial share of spending.

## Power BI Dashboard

The dashboard includes:

- KPI cards for average spending, total orders, and total customers.
- Customer count by country.
- Customer distribution by gender.
- Revenue by country.
- Highest-spending customers.
- Preferred product category by customer count.
- Slicers for year, customer segment, and country.

Add the dashboard screenshot to  so visitors can preview the report directly on the GitHub repository.

## Data Quality Notes and Limitations

The analysis has important limitations that should be considered when interpreting the results:

1. **Customer age and order values:** The current cleaned dataset contains the same  value (46.65) and  value (1.4) for every customer. The notebook's missing-value code applies the mean to the whole column. These fields should be corrected from the raw data before age- or order-based conclusions are made.
2. **Dashboard consistency:** The supplied dashboard screenshot contains country and gender visuals that do not fully match the CSV-based calculations documented in the report. Check visual-level filters and confirm that the dashboard uses the intended dataset before presenting it.
3. **Unknown categories:** Some records have  values for country, gender, customer segment, or preferred category.
4. **No transaction-level data:** The dataset does not provide individual order dates, product-level transactions, or order values. It therefore cannot support detailed sales seasonality or product performance analysis.
5. **Future account dates:** The report identifies some account creation dates later than 15 November 2026; these should be validated with the data source.

These limitations are documented rather than hidden so that the findings are not overstated.

## Business Recommendations

- Test welcome offers or first-purchase campaigns to encourage customers with zero recorded spending to make a first purchase.
- Focus retention efforts on Premium and high-value customers.
- Consider targeted win-back campaigns for At-Risk customers.
- Review the customer-segment definitions and improve missing or  data.
- Validate the age, order, and dashboard figures before using them for business decisions.

## How to Explore This Project

1. Open the Jupyter Notebook in  to review the data preparation steps.
2. Open the SQL script in  to review the business questions and queries.
3. Open the Power BI file in  to interact with the dashboard.
4. Read the PDF report in  for the methodology, findings, limitations, and recommendations.

## Author

**Avadhesh Sahani**  
Entry-Level Data Analyst  
Skills demonstrated: Python, Pandas, PostgreSQL, SQL, Power BI, data cleaning, data analysis, dashboard development, and business insights.

