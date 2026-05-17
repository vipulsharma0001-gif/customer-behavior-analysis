# Data Analytics Project – End-to-End Business Insights

## Overview

This project demonstrates a complete Data Analytics workflow starting from data collection and preprocessing to visualization and business insight generation. The objective of this project is to analyze the dataset, identify patterns, clean inconsistent data, perform SQL-based analysis, and create an interactive Power BI dashboard for decision-making.

The project includes:

* Data Loading and Understanding
* Exploratory Data Analysis (EDA)
* Data Cleaning and Transformation
* SQL Query Analysis
* Dashboard Creation using Power BI
* Business Insights and Findings

---

## Dataset

The dataset contains customer purchasing behavior and sales-related information including:

* Customer Details
* Product Categories
* Purchase Amounts
* Ratings and Reviews
* Payment Methods
* Subscription Status
* Seasonal Trends
* Purchase Frequency

### Sample Columns

* `customer_id`
* `age`
* `gender`
* `category`
* `purchase_amount`
* `review_rating`
* `payment_method`
* `discount_applied`
* `frequency_of_purchases`

---

## Tools and Technologies Used

| Tool                 | Purpose                    |
| -------------------- | -------------------------- |
| Python               | Data Cleaning and EDA      |
| Pandas               | Data Manipulation          |
| NumPy                | Numerical Operations       |
| Matplotlib / Seaborn | Data Visualization         |
| SQL                  | Data Querying and Analysis |
| Power BI             | Interactive Dashboard      |
| Excel / CSV          | Dataset Storage            |

---

## Exploratory Data Analysis (EDA)

Performed detailed EDA to understand:

* Customer purchasing trends
* Top-performing product categories
* Seasonal sales distribution
* Average purchase behavior
* Payment method preferences
* Impact of discounts on purchases

### Key EDA Tasks

* Handling missing values
* Removing duplicates
* Data formatting
* Statistical summaries
* Correlation analysis
* Visual trend analysis

---

## Data Cleaning

Data preprocessing steps included:

* Handling null or missing values
* Removing duplicate records
* Correcting inconsistent data types
* Standardizing categorical values
* Renaming columns for better readability

---

## SQL Analysis

Used SQL queries for extracting meaningful business insights such as:

* Customers spending above average
* Most purchased categories
* Discount usage analysis
* Revenue trends
* Customer segmentation

### Example SQL Query

```sql
SELECT customer_id, purchase_amount
FROM customer_purchases
WHERE discount_applied = 'Yes'
AND purchase_amount >
(
    SELECT AVG(purchase_amount)
    FROM customer_purchases
);
```

---

## Power BI Dashboard

Created an interactive dashboard to visualize:

* Total Revenue
* Customer Distribution
* Top Product Categories
* Seasonal Sales Trends
* Discount Impact Analysis
* Purchase Frequency Insights

### Dashboard Features

* Interactive Filters and Slicers
* KPI Cards
* Dynamic Charts
* Category-wise Analysis
* User-friendly Interface

---

## Results and Insights

Some important findings from the analysis:

* Customers using discounts often made higher-value purchases.
* Certain product categories generated significantly more revenue.
* Seasonal trends strongly influenced customer buying behavior.
* Digital payment methods were the most preferred among customers.

---

## Project Workflow

```text
Dataset → Data Cleaning → EDA → SQL Analysis → Visualization → Business Insights
```

---

## Dashboard Preview

Add your Power BI dashboard screenshots here.

---

## Project Structure

```text
├── Dataset
├── Python Scripts
├── SQL Queries
├── Power BI Dashboard
├── Visualizations
└── README.md
```

---

## Conclusion

This project demonstrates practical skills in:

* Data Analysis
* SQL Querying
* Data Visualization
* Business Intelligence
* Dashboard Development

The analysis transforms raw data into actionable insights that support better business decision-making.
