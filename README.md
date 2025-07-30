# 📦 eCommerce Store Data Analysis

This project showcases the analysis of **eCommerce sales data** for multiple platforms. The dataset includes order information, customer demographics, product details, and shipping information. The goal is to explore patterns in sales, customer behavior, and delivery trends using **Excel** or other analytical tools.



## 🧾 Table of Contents

* [About the Project](#about-the-project)
* [Dataset Description](#dataset-description)
* [Features and Insights](#features-and-insights)
* [Tools Used](#tools-used)
* [How to Use](#how-to-use)



## 📌 About the Project

This project is designed to analyze **sales transactions** across various eCommerce platforms such as **Myntra**, **Ajio**, **Amazon**, **Flipkart**, and **Meesho**. The dataset includes details such as:

* **Customer demographics**: Gender, Age group
* **Order details**: Order ID, SKU, Category, Size, Quantity
* **Sales data**: Amount, Currency
* **Shipping information**: City, State, Postal code, Country
* **Business model**: B2C transactions

The goal is to uncover insights such as:

* Popular products and categories
* Age-based purchasing trends
* Regional shipping patterns
* Transaction trends by platform

---

## 📋 Dataset Description

The dataset consists of transaction records with the following columns:

| Column Name        | Description                                          |
| ------------------ | ---------------------------------------------------- |
| `Index`            | Row index                                            |
| `Order ID`         | Unique identifier for each order                     |
| `Cust ID`          | Unique customer identifier                           |
| `Gender`           | Gender of the customer                               |
| `Age`              | Age of the customer                                  |
| `Age group`        | Age category (Adult, Senior)                         |
| `Date`             | Date of order                                        |
| `Month`            | Month of the transaction                             |
| `Status`           | Delivery status (e.g., Delivered)                    |
| `Channel`          | E-commerce platform where the order was placed       |
| `SKU`              | Stock Keeping Unit, unique product identifier        |
| `Category`         | Product category (e.g., Kurta, Western Dress)        |
| `Size`             | Product size (e.g., M, XL, XXL)                      |
| `Qty`              | Quantity of the product purchased                    |
| `Currency`         | Currency used for the transaction (INR)              |
| `Amount`           | Total amount for the order                           |
| `Ship-city`        | City where the product was shipped                   |
| `Ship-state`       | State where the product was shipped                  |
| `Ship-postal-code` | Postal code for the shipping address                 |
| `Ship-country`     | Country of delivery                                  |
| `B2B`              | Whether the transaction is a B2B sale (`TRUE/FALSE`) |
| `Business Type`    | Type of business (B2C or B2B)                        |

---

## ✨ Features and Insights

* **Customer Demographics**: Analysis of age, gender, and regional purchasing behavior.
* **Sales Patterns**: Analysis of transaction amounts, product categories, and quantity sold.
* **Shipping Trends**: Mapping regional shipping trends based on the city, state, and postal code.
* **eCommerce Platform Comparison**: Performance comparison of different eCommerce platforms (Myntra, Amazon, Flipkart, etc.).
* **Business Type Breakdown**: Analysis of B2C vs. B2B transactions and their trends.

---

## 🛠 Tools Used

* **Microsoft Excel** (for data cleaning, analysis, and visualization)

  * Pivot Tables
  * Conditional Formatting
  * Charts and Graphs
  * Excel Formulas (SUM, AVERAGE, IF, etc.)

* **Google Sheets** (for collaborative work)

* **Python** (optional for advanced analysis and visualizations, using libraries such as Pandas and Matplotlib)

---

## 🚀 How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/eCommerce-Sales-Data-Analysis.git
   ```

2. Open the dataset file:

   * `eCommerce_Sales_Data.xlsx`
   * You can use Excel, Google Sheets, or a Python environment.

3. Explore the sheets:

   * **Raw Data**: View and analyze the raw transaction data.
   * **Sales Analysis**: Pivot tables and charts summarizing sales insights.
   * **Regional Trends**: Analysis of shipping and customer location.

