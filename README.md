# Power BI - Food and Beverage Sales Dashboard

## Introduction
This project analyzes and visualizes the **Food and Beverage Sales Data** using Power BI. The dataset, sourced from Kaggle, contains essential attributes required for creating dashboards and meaningful visualizations. The dataset is in Excel (`.xlsx`) format and can be imported directly into Power BI.

Power BI is a **unified, scalable platform** that enables self-service and enterprise-level business intelligence. It allows users to connect to various data sources, perform data preprocessing, and create insightful dashboards.

---

## Data Collection
**Data collection** is the process of gathering, measuring, and analyzing data to extract insights. In this project, the dataset consists of two Excel files:

- **Product.xlsx** 
  - Columns: 4
  - Rows: 799

- **SalesData.xlsx**
  - Columns: 10
  - Rows: 999+

The **Food and Beverage Sales Analysis Dashboard** provides insights into revenue trends, product demand, and regional performance, aiding in inventory management and customer satisfaction.

🔗 Dataset: [Kaggle - Sales and Product Data](https://www.kaggle.com/datasets/emmanuelbassey94/sales-and-product-data/)

---

## Data Preparation and Modeling

### 1. Data Cleaning
Data cleaning ensures accuracy and consistency by handling missing values and removing inconsistencies:
- **Missing values handling strategies:**
  - Ignoring tuples with multiple missing attributes
  - Manually filling missing values
  - Replacing missing values with global constants, attribute means, or most likely values

### 2. Data Transformation
Data transformation converts data into the required format:
- Changing data structures and formats
- Performing calculations, translations, and summarizations
- Applying DAX measures and column transformations

### 3. Data Modeling
Data modeling establishes relationships between multiple tables to enable efficient data analysis. Types of relationships:
- **One-to-One**
- **One-to-Many**
- **Many-to-One**
- **Many-to-Many**

---

## Data Analysis & Interpretation

**Data analysis** involves turning raw data into meaningful insights using Power BI visuals and queries. It includes:
- Creating various charts and dashboards
- Analyzing and visualizing data across multiple dimensions
- Deriving insights and business conclusions

### DAX (Data Analysis Expressions)
DAX functions are used for calculations and data manipulation. Some DAX queries used in this project:
```DAX
Revenue = SUM(Sheet1[Sale Amount])
Order = DISTINCTCOUNT(Sheet1[OrderNumber])
ATP = DIVIDE('Product'[Revenue],'Product'[Order],"")
Sale Amount = Sheet1[Quantity] * Sheet1[UnitPrice]
```

### Chart Queries
1. Total revenue of all products
2. Average total price of products
3. Total number of orders
4. Revenue distribution across sales channels
5. Revenue breakdown by product category
6. Donut chart for order distribution across categories
7. Revenue and order trends by quarter
8. Bar chart comparison of product group revenue
9. Monthly revenue and order volume tracking
10. Top 3 salespeople by revenue (bar chart)
11. Top 4 salespeople by order value (ranking)
12. Heat map for orders, ATP, and revenue by salesperson
13. Top products by revenue within each category and sales channel
14. Total quantity sold per manager
15. Orders placed through each sales channel

---

## Publishing the Dashboard
Power BI dashboards provide interactive visual representations of key metrics. Dashboards consolidate insights from multiple datasets and refresh dynamically with updated data.

### Steps to Publish Dashboard
#### Step 1: Import Data
1. Open Power BI Service in a web browser
2. Click **Get Data** (bottom-left corner)
3. Select **Import Data from Local Disk**
4. Upload the **Food and Beverage Sales Analysis Dashboard** file

#### Step 2: Create Dashboard
1. Select visuals from the imported Power BI file
2. Create a new dashboard named **"FOOD AND BEVERAGE SALES DASHBOARD"**
3. Pin visuals to the dashboard

🔗 **Dashboard Link**: [Power BI Dashboard](https://app.powerbi.com/groups/me/dashboards/111ee77a-9924-4fbe-98fb5c2382a5bee2?experience=power-bi)

---

## Conclusion
This Power BI project provides valuable insights into sales trends, product demand, and revenue performance. It demonstrates the complete data analysis pipeline, from **data collection and cleaning** to **visualization and reporting**. The interactive dashboard serves as a powerful tool for business intelligence and decision-making.

---

### 📌 Author: [MAHALAKSHMI ELANGOVAN]
### 🏆 Technologies Used: Power BI, DAX, Excel
### 📂 Repository: [GitHub Repository Link]


