# Grocery Store Sales Analysis with PySpark

## Project Overview

This project analyzes a grocery store chain sales dataset using **PySpark**.
The dataset contains transactional sales data from **9 grocery store locations**, covering multiple product categories, customers, and promotional discounts over a two-year period (2023–2025).

The objective is to apply **data engineering and analytical techniques** to clean, transform, and analyze sales data in order to extract meaningful business insights.

---

## Project Objectives

* Load and explore a real-world sales dataset
* Clean and preprocess inconsistent and missing data
* Perform exploratory and analytical queries using PySpark
* Analyze store performance, product popularity, and sales trends
* Demonstrate practical data engineering and analytics skills

---

## Dataset Description

The dataset used in this project is the **Grocery Store Sales Dataset (2025)** sourced from Kaggle.

### Key Characteristics

* Total Records: ~1,980 transactions
* Time Period: August 2023 – August 2025
* Store Locations: 9 grocery stores
* Product Categories: 11 aisles
* Data Quality: Includes missing values, inconsistent formats, and negative values for realistic cleaning practice

### Main Columns

* customer_id
* store_name
* transaction_date
* aisle
* product_name
* quantity
* unit_price
* total_amount
* discount_amount
* final_amount
* loyalty_points

Note: The dataset is **not included in this repository** due to licensing and size considerations.
The analysis pipeline is designed to work with any similarly structured grocery sales dataset.

---

## Notebook

The analysis is implemented in the following notebook:

* notebooks/data_engineering_project_2.ipynb

---

## Key Analysis Performed

* Sales distribution across store locations
* Product and aisle-level sales analysis
* Transaction value and discount analysis
* Identification of high-performing stores and products
* Handling of missing values and data inconsistencies
* Validation of negative and edge-case values

---

## Technologies Used

* Apache Spark (PySpark)
* Python
* Jupyter Notebook / Databricks
* Pandas (for auxiliary analysis)

---

## Key Skills Demonstrated

* Data ingestion and preprocessing
* PySpark DataFrame transformations
* Exploratory data analysis (EDA)
* Business-oriented data insights
* Clean and well-documented notebooks

---

## License

This project is licensed under the MIT License.

---

## Author

Amira Ouaked
MSc Data Engineering & Data Science
