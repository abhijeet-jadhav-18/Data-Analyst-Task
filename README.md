# Data-Analyst-Task

## Task 1:

# Sales Dataset CRUD Operations

This project demonstrates **CRUD (Create, Read, Update, Delete) operations** on a sales dataset stored in a CSV file using Python and Pandas.

##  Features
- **Create** → Insert new sales records  
- **Read** → Retrieve records based on product name  
- **Update** → Modify existing sales records (price/quantity)  
- **Delete** → Remove specific records using SaleID

-  Python 3  
- Pandas library  
- CSV file for dataset storage  

## 📂 Dataset Example
| SaleID | Product     | Quantity | Price  |
|--------|------------|----------|--------|
| 1      | Laptop     | 2        | 50000  |
| 2      | Mobile     | 5        | 15000  |
| 3      | Tablet     | 3        | 18000  |
| 4      | Headphones | 10       | 2000   |

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Task 2: Descriptive and Predictive Analysis with Interactive Dashboard
Take any sales dataset of your choice and perform both descriptive and predictive analysis.
Create an interactive dashboard using Python visualization libraries such as Plotly or Dash.
Ensure that the graphs are interactive and can cross-filter each other. Include at least three
different types of visualizations.

#  Descriptive and Predictive Analysis with Interactive Dashboard

This project demonstrates **Descriptive and Predictive Analysis** on a sales dataset using **Python, Pandas, Plotly, and Dash**.  
It provides an **interactive dashboard** where users can explore sales data, analyze trends, and predict future sales.

## Features

###  Descriptive Analysis
- Summary statistics (mean, max, min, std) of **Sales** and **Profit**
- Aggregations:
  - Sales by **Category**
  - Profit by **Region**
  - Monthly Sales trends
- Helps answer:  
  - *Which products are selling most?*  
  - *Which region is most profitable?*  
  - *How do sales vary month-to-month?*

###  Predictive Analysis
- Built a **Linear Regression model** to predict **Sales based on Profit**
- Equation form:
  \[
  Sales = m \times Profit + c
  \]
- Example use case:  
  - If Profit = ₹1000 → Predict corresponding Sales
- Helps with **forecasting sales** and **business planning**

###  Interactive Dashboard
- Developed using **Dash + Plotly**
- Includes **3 interactive charts**:
  1.  **Bar Chart** – Sales by Product Category  
  2.  **Scatter Plot** – Sales vs Profit (with regression line)  
  3.  **Line Chart** – Monthly Sales Trend
 ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


 # Task 3: 
- Web Scraping for Product Details
Perform web scraping from two e-commerce websites (e.g., Amazon, Flipkart, Chroma,
Reliance Digital). Create a dynamic Python script that allows the user to search for products
and save the details (e.g., name, price, ratings) in an Excel file. Ensure the code is robust and
handles dynamic search queries.

##  Features
- **Dynamic Search Query** → User can input any product name (e.g., "Laptop", "iPhone", "Samsung S23")  
- **Multi-Website Scraping** → Collects product details from **Amazon** and **Flipkart**  
- **Data Extraction** → Scrapes:
  - Product Name  
  - Price  
  - Ratings / Reviews  
- **Data Export** → Saves results into a clean **Excel file (.xlsx)**  
- **Error Handling** → Skips missing values and handles invalid search results  
