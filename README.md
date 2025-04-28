### Microsoft Fabric - Lakehouse Creation 
This project demonstrates how to create and explore a Lakehouse in Microsoft Fabric, combining the flexibility of a data lake with the query capabilities of a data warehouse.

### Overview
Workspace creation with Fabric trial capacity

Lakehouse setup using OneLake storage (Azure Data Lake Gen2)

Data upload (sales.csv) into the Files section

Delta Table creation for SQL querying

SQL analytics endpoint usage for data analysis

Visual query building with Power Query

Power BI report creation based on lakehouse data

### Technologies
Microsoft Fabric (Lakehouse, OneLake)

Delta Lake table format

SQL Analytics Endpoint

Power BI Reporting

### Steps Followed
Created a workspace with Fabric capacity enabled.

Set up a new Lakehouse and explored file and table structures.

Uploaded sales.csv into a subfolder named data.

Loaded CSV data into a managed Delta table (sales).

Ran SQL queries to analyze product revenue.

Built a visual query to count line items per sales order.

Designed a clustered bar chart in Power BI and saved it as Item Sales Report.

### Key Takeaways
Lakehouses blend the best of data lakes and warehouses.

Delta tables allow for efficient, scalable SQL querying over file-based storage.

Fabric provides seamless integration between data storage, processing, and visualization.

### Clean-Up
After completing the lab, remember to remove the workspace to avoid unnecessary resource usage.

