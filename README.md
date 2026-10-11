# Retail Sales Data Cleaning

## Project Overview

This project focuses on cleaning and preparing a retail sales dataset for further data analysis. The dataset was examined for missing values, duplicate records, invalid dates, and statistical outliers.

## Dataset

The dataset contains **1,000 retail sales records** and **9 columns**, including:

* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price per Unit
* Total Amount

## Data Cleaning Steps

The following data cleaning operations were performed:

1. Loaded and inspected the dataset.
2. Checked column names and data types.
3. Checked for missing values.
4. Checked for duplicate records.
5. Converted the `Date` column into datetime format.
6. Checked for invalid dates.
7. Detected statistical outliers using the **IQR (Interquartile Range)** method.
8. Verified the dataset after cleaning.
9. Saved the cleaned dataset as a CSV file.

## Data Quality Results

* Total records: **1,000**
* Total columns: **9**
* Missing values: **0**
* Duplicate records: **0**
* Invalid dates: **0**
* Statistical outliers detected using IQR: **0**

## Tools & Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Project Files

* `Data_Cleaning.ipynb` — Jupyter Notebook containing the data cleaning process.
* `retail_sales_dataset.csv` — Original dataset.
* `cleaned_retail_sales_dataset.csv` — Cleaned dataset.

## Conclusion

The dataset was successfully cleaned and validated. There were no missing values, duplicate records, invalid dates, or statistical outliers according to the applied checks. The cleaned dataset is ready for further analysis and visualization.
