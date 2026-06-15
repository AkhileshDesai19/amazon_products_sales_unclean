# Amazon Product Sales Data Cleaning with Pandas

## Project Overview

This project focuses on cleaning and preprocessing an Amazon Product Sales dataset using Python and Pandas.

The raw dataset contained missing values, inconsistent formatting, incorrect data types, unnecessary columns, and textual information that required transformation before analysis.

The goal was to prepare a clean and analysis-ready dataset suitable for Exploratory Data Analysis (EDA), visualization, and business reporting.

---

## Dataset Features

The dataset includes information such as:

* Product Title
* Product Rating
* Number of Reviews
* Bought in Last Month
* Current/Discounted Price
* Listed Price
* Best Seller Badge
* Sponsored Status
* Coupon Information
* Delivery Details
* Collection Date

---

## Data Cleaning Steps Performed

### 1. Initial Data Inspection

* Checked dataset shape
* Inspected column data types
* Generated summary statistics
* Identified missing values
* Checked duplicate records

### 2. Removed Unnecessary Columns

Dropped:

* image_url
* product_url

These columns contained URLs and were not required for analysis.

### 3. Handled Missing Values

* Filled missing ratings using median values
* Filled missing review counts using median values
* Filled missing purchase counts using median values
* Filled missing prices using median values
* Filled missing buy box information with "Unknown"

### 4. Data Type Corrections

Converted columns to appropriate data types:

* Float
* Integer
* Datetime
* Category

### 5. Text Cleaning

* Removed extra spaces
* Standardized text formatting
* Converted product titles to lowercase
* Cleaned coupon and badge information

### 6. Feature Extraction

Extracted:

* Delivery Date
* Delivery Range

from delivery details text.

### 7. Duplicate Validation

Checked for duplicate records and validated data consistency.

### 8. Dataset Optimization

Converted low-cardinality text columns into category data types to reduce memory usage.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

---

## Outcome

The dataset was transformed from a raw, unclean format into a structured and analysis-ready dataset.

The cleaned dataset can now be used for:

* Exploratory Data Analysis (EDA)
* Dashboard Creation
* Business Insights
* Machine Learning Projects

---

## Author

Akhilesh Desai

Aspiring Data Analyst | Python | SQL | Excel | Power BI
