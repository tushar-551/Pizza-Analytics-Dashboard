# Pizza Sales Analysis with Power BI

This project involves analyzing pizza sales data using Microsoft Power BI. The data was imported from an MS SQL Server database and then transformed, modeled, and visualized in Power BI Desktop.

## Data Source

The data for this project was obtained from a SQL Server database containing transactional data related to pizza sales. The relevant tables were imported into Power BI for analysis. [pizza-sales-data](https://github.com/tushar11720/pizza-sales-analysis)

## Data Transformation

The following steps were performed for data transformation and preparation:

1. **Data Cleaning**: Handled missing values, removed duplicates, and standardized data formats.
2. **Data Merging**: Joined multiple tables from the database to create a consolidated dataset for analysis.
3. **Calculated Columns**: Created new calculated columns using DAX formulas to derive additional metrics and insights.

## Data Modeling

The data model was designed using the star schema approach, with a central fact table (pizza sales transactions) and related dimension tables (product, customer, time, etc.). Appropriate relationships were established between the tables.

## DAX Calculations

Several DAX measures and calculations were created to analyze key performance indicators (KPIs) and metrics, such as:

- Total Revenue
- Average Order Value
- Total Pizza Sold
- Total Orders
- Average Pizzas per Order
- Sales by Pizza Size
- Sales by Pizza Category
- Best-selling and Worst-selling Pizzas (by Revenue, Quantity, and Total Orders)

## Visualizations

The project includes a variety of visualizations to represent the data and insights effectively. Some of the key visualizations are:

- Daily and Monthly Trends for Total Orders
- Percentage of Sales by Pizza Size and Category
- Total Pizza Sold by Pizza Category
- Best and Worst Sellers (based on Revenue, Quantity, and Total Orders)
- Busiest Days and Times for Orders

## Report Gallery

This section showcases some of the key reports and visualizations created in this project.

### Home Page

![image](https://github.com/tushar11720/Netflix-Dashboard/assets/132842128/2021f8ee-0687-4e68-bc6a-bcd3f5b597ce)

The home page provides an overview of the key metrics and performance indicators for pizza sales, including total revenue, average order value, total pizzas sold, total orders, and average pizzas per order. It also displays visualizations for daily and monthly trends in total orders, as well as breakdowns of sales by pizza size and category.

### Best and Worst Sellers

![image](https://github.com/tushar11720/Netflix-Dashboard/assets/132842128/b37c24c0-bac8-4d18-ab28-36ca5dec83ba)

The "Best and Worst Sellers" report page highlights the top-performing and underperforming pizza varieties based on different metrics such as revenue, quantity sold, and total orders. This report helps identify the most popular and least popular pizza offerings, enabling data-driven decisions for menu optimization and promotional strategies.

## Usage

To explore the analysis and visualizations, open the `Pizza.pbix` file in Power BI Desktop. The report is divided into multiple pages, each focusing on a specific aspect of the analysis.
