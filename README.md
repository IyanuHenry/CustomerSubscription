# Customer Sales Data

### Project Overview
To analyze the sales performance of a retail store, this project explores sales data such as top-selling products, regional performance, and monthly sales trends.

### Data Source
The source of the data was provided by Incubator Hub, which is an educational tech platform.

### Tools Used
Microsoft Excel:
 - Data cleaning
 - Utilized Excel formulas to calculate metrics such as average sales, total revenue, and sales revenue using the formula =SUM(Quantity * Unit Price).
 - Visualization using pivot tables and charts to represent sales trends and performance.

SQL:
- Extracted key insights using queries to aggregate sales data and identify trends.
- Employed commands such as ALTER TABLE and DELETE to clean data by removing unnecessary columns and handling null values.

Power BI:
- Built dashboards for visualizing sales performance metrics.

### Data Cleaning and Preparation
1. Data Loading and Inspection
   Microsoft Excel:
   -Imported data into Excel, expanded the worksheet table, and removed duplicates using the Data tab.
   
   SQL Server: 
   - Created a new database, imported data, and checked for duplicates and unnecessary columns.

   Power BI: 
   - Imported data and checked column distributions to identify duplicates and blanks.

2. Handling Missing Variables
   Microsoft Excel:
   - Added a column for sales revenue using the formula =SUM(Quantity * Unit Price).
     
   SQL:
   - Used IS NULL to identify missing values and deleted rows with null CustomerID.
     
   Power BI:
   - Handled missing values using transformation tools in the Power Query Editor.
   
4. Data Cleaning and Formatting
   Microsoft Excel:
   - Standardized formats for dates and currency, ensuring calculations were accurate.
     
   SQL:
   - Checked and adjusted data types for consistency using ALTER TABLE and formatting functions.
     
   Power BI:
   - Applied consistent formats and renamed columns in the Power Query Editor.

### Data Analysis Process
The data analysis process for the retail store sales data involved several key steps to extract meaningful insights and support decision-making.
1. Data Exploration
   - Initial Review: Conducted an initial inspection of the dataset to understand its structure and assess data completeness, identifying key variables such as order ID, product type, quantity sold, unit price, and region.
     
2. Revenue Calculation
   - Total Revenue: Calculated by multiplying the quantity sold by the unit price, providing a clear measure of overall sales.
   - Average Revenue: Used Excel to determine average revenue, establishing a baseline for typical sales performance.
   - Regional Revenue Analysis: Applied the AVERAGEIF function in Excel to calculate average revenue by region (e.g., South region), enabling comparative analysis.
   - Regional Sales Contribution: Calculated the percentage of total sales contributed by each region, offering insights into regional performance.

     ![excel table](https://github.com/user-attachments/assets/d097427a-a502-40e5-a3d9-a6649cdd2037)

3. Top-Selling Products
   - Product Analysis: Grouped sales data by product category and calculated the total revenue for each category, identifying top-selling products to inform inventory planning and promotional strategies.

4. Trend Analysis
   - Monthly Sales Trends: Created visualizations in Power BI and Excel to observe monthly sales trends, pinpointing peak sales periods and seasonal demand.
   - Regional Performance Comparison: Analyzed regional sales data to identify performance discrepancies, using SQL to generate summary statistics and visualizations for deeper insights.
  
     ![monthly product](https://github.com/user-attachments/assets/fe75f680-46f9-44b9-9b89-4d043bac96c6)

     
5. Insights and Reporting
   - Actionable Insights: Derived insights included focusing on high-demand products, amplifying marketing in strong-performing regions, and preparing for peak sales periods based on observed trends.
   - Reporting: Findings were presented in structured tables and visualizations to support strategic planning and decision-making.



