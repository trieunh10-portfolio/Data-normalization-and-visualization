# Data normalization and visualization
Develop a clean dataset with readable information for further analysis and create a dashboard report on sales over the years.
## Data
- Du_lieu_In dataset: 700 rows, 6 columns.
- Truc_quan_hoa dataset: 4 tables (Calendar, Customers, Products, Sales) that have been data modeled according to the Star Schema.
## Tools and Technique
- Excel: Power Query, Power Pivot, Pivot Table and Pivot Chart.
## Process
1. Work with the Du_lieu_In dataset:
- Data cleaning by Power Query: split columns, replaced Null values, converted data type, filtered data.
- Data modeling: split the cleaned dataset into Fact table (Financials table) and Dimension tables (Products and Geography tables). Create relationships between these tables.
2. Work with the data model in the Truc_quan_hoa dataset:
- Data exploration with DAX measure in Power Pivot: [DAX Formulas in Power Pivot](https://github.com/trieunh10-portfolio/Data-normalization-and-visualization/blob/main/DAX%20Formula%20in%20Power%20Pivot.md)
  
- Using Pivot Table for: calculated total sales, create top 10 products by total sales table.
- Create an interactive dashboard with Pivot Chart

- Dashboard image: [Bike Enjoys dashboard](https://github.com/trieunh10-portfolio/Data-normalization-and-visualization/blob/main/Bike%20Enjoys%20dashboard.jpg)
