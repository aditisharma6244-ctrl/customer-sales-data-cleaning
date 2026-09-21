# Customer Sales Data Cleaning and Preprocessing

## Project Overview

This project demonstrates the process of transforming raw and unstructured customer sales data into a clean, consistent, and analysis-ready dataset.

The raw dataset contains common real-world data quality issues such as duplicate records, missing values, inconsistent formats, invalid numerical values, and malformed email addresses.

## Objective

The objective of this project is to design a data-cleaning process that improves data quality while preserving data integrity.

## Dataset

The dataset contains the following information:

- Customer ID
- Name
- Age
- Gender
- City
- Purchase Date
- Product
- Sales Amount
- Email

## Data Quality Issues Identified

The raw dataset contained:

- Duplicate records
- Missing values
- Extra spaces in text
- Inconsistent capitalization
- Inconsistent gender formats
- Inconsistent city names
- Multiple date formats
- Invalid age values
- Negative sales values
- Missing sales values
- Invalid email formats

## Data Cleaning Process

The following steps were performed:

1. Loaded and inspected the raw dataset.
2. Identified and removed duplicate records.
3. Removed unnecessary spaces from text fields.
4. Standardized names using title case.
5. Standardized gender values.
6. Standardized city names.
7. Standardized product names.
8. Converted different date formats into a consistent format.
9. Identified and handled invalid age values.
10. Handled missing age values using the median.
11. Identified and handled negative sales values.
12. Handled missing sales values using the median.
13. Handled missing categorical values where appropriate.
14. Validated email addresses.
15. Preserved unknown information instead of creating false values.
16. Performed final validation of the cleaned dataset.

## Data Integrity

Data integrity was considered throughout the cleaning process.

Duplicate records were removed, while unique customer records were preserved.

For values that could not be reliably determined, such as an unknown purchase date or email address, the information was kept as missing rather than inventing values.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Google Colab

## Project Files

| File | Description |
|---|---|
| `raw_customer_sales.csv` | Original raw dataset containing data-quality issues |
| `cleaned_customer_sales.csv` | Cleaned and standardized dataset |

## Result

The raw customer sales dataset was transformed into a cleaner and more consistent format suitable for further analysis.

The cleaning process addressed duplicate records, missing values, inconsistent text and date formats, invalid numerical values, and malformed email addresses while maintaining data integrity.

## Conclusion

This project demonstrates a systematic approach to real-world data cleaning and preprocessing. The resulting cleaned dataset can be used as a reliable input for further data analysis and machine learning workflows.
