**Credit Card Data Analysis with Power BI**

This project showcases a comprehensive analysis of credit card data using Power BI, with data sourced from CSV files and loaded into MySQL. The analysis focuses on customer insights and transaction patterns, providing valuable business intelligence.

**Project Overview**

The project consists of two main report pages in Power BI:

**Customer Report Page**

Slicers: Gender, marital status, customer job type, monthly and quarterly revenue.

**Visualizations:**

Stacked bar charts for customers by age group, dependent count, and marital status.

Bar chart for the top 5 cities with the most customers and their education levels.

Donut charts for home ownership, personal loan status by income group.

**KPIs:**

Minimum and maximum credit limits.

Account activation in the last 30 days.

Customer satisfaction score (CSS): 3.19.

Total customers and more.

**Transaction Report Page**

**Visualizations:**

Bar charts for quarterly revenue and transaction counts.

Revenue by expenditure type, emphasizing bills as the primary usage reason.

Revenue by card category (Blue card: $46.1M, Graduate education level: $22.3M).

Slicers: Date range, total revenue KPIs for male and female.

Line chart for monthly revenue fluctuations.

Donut charts for total transaction count, amount, and interest earned.

**Technical Details**

Data Loading: CSV data was loaded into MySQL using the LOAD DATA command.

Data Transformation: Power BI was connected to the MySQL server for data transformation and analysis.

DAX Queries: Used to separate age into age groups and income into Low, Medium, and High categories.


Prerequisites
**MySQL server
Power BI Desktop**

**Steps:**
**Load Data into MySQL:**
Use the LOAD DATA command to import the CSV file into the MySQL database.

**Connect Power BI to MySQL:**
Establish a connection between Power BI and the MySQL server.

**Transform Data in Power BI:**
Use Power Query for data transformation and DAX queries for calculated columns.

**Create Visualizations:**
Build the reports using various Power BI visualizations and KPIs.

Acknowledgments
Thanks to the open-source community for providing tools and resources that made this project possible.
