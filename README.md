# Customer Sales Data

### Project Overview
To analyze the sales performance of a retail store, this project explores sales data such as top-selling products, regional performance, and monthly sales trends.

### Outline
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis Process](#data-analysis-process)
- [Data Visualization](#data-visualization)
- [Insights and Findings](#insights-and-findings)
- [Conclusion](#conclusion)

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

   ![delete rows and columns](https://github.com/user-attachments/assets/b323a84f-3e10-4ba9-9c1b-c5ac859c9494)

     
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
   - Product Analysis: Grouped sales data by product category and calculated the total revenue for each category, 

4. Trend Analysis
   - Monthly Sales Trends: Created visualizations in Power BI and Excel to observe monthly sales trends, pinpointing peak sales periods and seasonal demand.
   - Regional Performance Comparison: Analyzed regional sales data to identify performance discrepancies, using SQL to generate summary statistics and visualizations for deeper insights.
  
     ![monthly product](https://github.com/user-attachments/assets/fe75f680-46f9-44b9-9b89-4d043bac96c6)



### Data Visualization 
Visualizations provided clear insights into sales performance, product demand, and regional trends, aiding in decision-making.

1. Revenue and Regional Sales Contribution
   - KPI Cards: Use KPI (Key Performance Indicator) cards for Total Revenue and Average Revenue. These provide a clear and quick of overall performance metrics.
   - Sales Contribution Percentage: The pie chart shows each region's share of total sales.

2. Top-Selling Products
   - Table Visualization: Display each product with its total sales revenue to show revenue by product category.
     
3. Count of Product by Region:
   - Pie Chart: The pie chart is showing the proportion of product counts across regions (East, North, South, West) for the overview of regional product distribution.
     
  
   ![power Bi](https://github.com/user-attachments/assets/5b586680-29c9-4e94-9efc-9c635ed392b1)

### Insights and Findings

1. Total Revenue: The store brought in 2,101,090 in total revenue, reflecting solid sales overall.
   
2. Top Products: Shirts and Shoes are driving the most revenue, with Shirts alone contributing 485,600. These products are clear favorites among customers.
   
3. Low-Performing Products: Gloves and Socks had the lowest sales, with revenues of 296,900 and 180,785, respectively. These items may need extra promotion or adjustments in stock to boost sales.
   
4. Regional Distribution: Each region (East, North, South, and West) contributes about 25% to the total product count, showing balanced market coverage. This equal distribution highlights a broad customer reach across regions.
   
5. Average Transaction Value: The average revenue per transaction is 212. This can be a benchmark for increasing transaction values through upselling or bundling products.
    
6. Order Volume by Region: Order counts are similar across regions, indicating consistent customer engagement. However, identifying regions with higher revenue can help refine marketing and inventory focus.

### Conclusion
The data shows that the retail store has strong sales overall, with Shirts and Shoes leading in revenue and balanced demand across regions. Focusing on boosting sales for Gloves and Socks and increasing the average transaction value can further enhance performance. The store is well-positioned to grow by leveraging these insights for targeted improvements.

