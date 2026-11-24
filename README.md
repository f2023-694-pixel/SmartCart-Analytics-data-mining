# SmartCart Analytics – Grocery Customer and Purchase Pattern Analysis

## Project Overview

SmartCart Analytics is a Data Warehousing and Mining project focused on analyzing grocery shopping data to understand customer purchasing behaviour, product preferences, and shopping patterns.

The project uses Python and Pandas to clean, integrate, process, and analyze multiple grocery datasets. Different data mining techniques are applied to identify useful patterns, make predictions, and generate business insights.

## Problem Statement

Grocery businesses collect large amounts of customer transaction data. However, understanding customer behaviour, identifying popular products, and predicting purchasing patterns can be challenging.

This project uses data mining techniques to analyze grocery shopping records and discover meaningful insights that can help businesses improve customer understanding, product recommendations, and inventory planning.

## Project Objectives

- Collect and integrate multiple grocery shopping datasets.
- Clean and preprocess raw data for analysis.
- Predict the number of days between customer orders.
- Predict whether a product will be reordered.
- Identify products frequently purchased together.
- Segment customers based on their purchasing behaviour.
- Evaluate models and interpret the results.
- Generate useful business insights from the analysis.

## Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Mlxtend
- Google Colab

## Datasets Used

The project uses five CSV datasets:

| Dataset | Description |
|---|---|
| `orders.csv` | Contains customer order information. |
| `order_products__train.csv` | Contains products purchased in each order. |
| `products.csv` | Contains product details and names. |
| `aisles.csv` | Contains product aisle information. |
| `departments.csv` | Contains grocery department details. |

## Project Workflow

The project follows these steps:

### 1. Data Collection
Collected five grocery shopping datasets containing order details, purchased products, product information, aisles, and departments.

### 2. Data Loading
Imported the CSV files into Google Colab using Python and Pandas.

### 3. Data Understanding
Examined the datasets, their columns, data types, number of records, and missing values to understand the available information.

### 4. Data Cleaning and Preprocessing
- Checked for duplicate records and missing values.
- Removed unnecessary or incomplete records.
- Prepared the data for further analysis.

### 5. Data Integration
Combined the five datasets using common columns and identifiers such as `order_id`, `product_id`, `aisle_id`, and `department_id`. Created one integrated dataset for analysis.

### 6. Data Mining and Analysis

Applied four data mining techniques:

- **Linear Regression:** Predicted the number of days between customer orders.
- **Logistic Regression:** Predicted whether a product would be reordered.
- **FP-Growth:** Identified products frequently purchased together and generated association rules.
- **K-Means Clustering:** Grouped customers according to their purchasing behaviour.

### 7. Model Evaluation
- Evaluated regression and classification models using performance metrics.
- Examined frequent itemsets and association rules.
- Reviewed customer clusters and their characteristics.

### 8. Data Visualization
Created visualizations to understand customer segments and compare actual and predicted order intervals.

### 9. Results and Insights
Interpreted the findings to identify customer purchasing patterns, product preferences, and reorder behaviour.

### 10. Output Generation
Exported the analysis results, model predictions, association rules, and customer segments into CSV files.

## Data Mining Techniques

### 1. Linear Regression
Used to predict the number of days between customer orders based on order-related features.

### 2. Logistic Regression
Used to classify whether a product in an order is a reorder or a first-time purchase.

### 3. FP-Growth Association Rule Mining
Used to discover products that are frequently purchased together. Association rules help identify relationships between grocery products.

### 4. K-Means Clustering
Used to divide customers into three groups based on their total orders, average days between orders, and average shopping hours.

## Key Project Outcomes

- Identified popular grocery products and departments.
- Analyzed customer reorder behaviour.
- Discovered frequently purchased product combinations.
- Predicted customer ordering patterns.
- Grouped customers according to their shopping behaviour.
- Generated visual insights to support business decisions.

## How to Run the Project

1. Open the project notebook in Google Colab.
2. Upload all five required CSV datasets.
3. Install the required libraries if they are not already available.
4. Run the notebook cells in sequence.
5. Review the model results, analysis, and visualizations.
6. Access the generated output files.

## Conclusion

This project demonstrates how data warehousing and data mining techniques can be applied to grocery shopping data to extract meaningful information. By using regression, classification, association rule mining, and clustering, the project identifies customer purchasing patterns, product relationships, and customer segments.

These insights can help grocery businesses better understand their customers, improve product recommendations, and make more informed business decisions.

---

**Project Name:** SmartCart Analytics  
**Course:** Data Warehousing and Mining  
**Programming Language:** Python  
**Platform:** Google Colab
