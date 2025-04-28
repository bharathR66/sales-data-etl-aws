# Sales Data ETL Pipeline (AWS + Power BI)

## Project Overview
This project demonstrates an end-to-end ETL pipeline for processing and analyzing sales order data.  
Data was ingested, cleaned, transformed using Python, stored on AWS S3, and visualized using Power BI.

## Technologies Used
- AWS S3 (Cloud Storage)
- Python (pandas, boto3)
- PandasSQL (for SQL-like transformations)
- Power BI (Visualization)

## Steps Performed
1. **Extract**: Loaded raw sales order dataset.
2. **Transform**:
   - Cleaned missing values.
   - Created new KPIs like total sales and monthly revenue.
   - Applied SQL-like queries for regional sales analysis and top product identification.
3. **Load**:
   - Uploaded cleaned datasets back into AWS S3 (processed zone).
4. **Visualization**:
   - Connected AWS S3 to Power BI to build dashboards for sales trends, product performance, and regional analysis.


## Key Highlights
- Simulated a cloud-based data engineering workflow using AWS services.
- SQL-style analysis performed within pandas using `pandasql`.
- Power BI dashboards built to derive business insights.

---
