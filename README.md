
# 🛒 E-Commerce Sales Analysis using Python

## Project Overview
This project focuses on analysing e-commerce transaction data to understand sales performance, customer purchasing behaviour and business trends.

The analysis is performed using Python, Pandas, NumPy, Matplotlib and Seaborn.

##  Project Objectives
- Analyse monthly revenue trends.
- Identify top-selling products.
- Identify high-value customers.
- Analyse country-wise sales performance.
- Perform RFM-based customer segmentation.
- Generate actionable business recommendations.

## Dataset Information
**Dataset:** UCI Online Retail Dataset

**Source:** https://archive.ics.uci.edu/dataset/352/online-retail

The dataset contains historical retail transaction records from December 2010 to December 2011.

### Important Columns
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

##  Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

##  Data Cleaning
- Checked and handled missing values.
- Removed duplicate records.
- Handled invalid transactions.
- Converted date columns into datetime format.
- Created a Revenue column.
- Detected outliers using the IQR method.

##  Exploratory Data Analysis
- Monthly Sales Analysis
- Top 10 Products by Revenue
- Top 10 Customers by Revenue
- Country-wise Revenue Analysis
- Day-wise Sales Analysis

##  Customer Segmentation (RFM)
RFM analysis was performed using:

- **Recency:** How recently a customer purchased.
- **Frequency:** How frequently a customer purchased.
- **Monetary:** How much money a customer spent.

Customer segments:
- Best Customers
- Loyal / Active Customers
- At Risk Customers
- Lost / Inactive Customers
- Potential Customers

##  Business Recommendations
1. Maintain inventory for high-revenue products.
2. Plan marketing campaigns before peak sales periods.
3. Offer loyalty rewards to valuable customers.
4. Target inactive customers with personalised offers.
5. Focus on high-performing geographical markets.
6. Track product costs to calculate actual profit margins.

##  Project Limitations
The dataset does not contain product cost or shipping cost information. Therefore, this project focuses on revenue analysis rather than actual profit calculation.

##  Project Files
- `ecommerce_sales_analysis_project.ipynb` – Complete Python analysis notebook.
- `README.md` – Project documentation.

##  Author
**Tanishk Singh**

Aspiring Data Analyst | Data Science Learner

Skills: Python | Pandas | NumPy | Data Analysis | Data Visualization
