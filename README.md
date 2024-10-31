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



