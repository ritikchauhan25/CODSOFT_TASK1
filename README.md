# CODSOFT Task 1 - Data Cleaning and Preprocessing

## Project Overview

This project was completed as part of the CODSOFT Data Analytics Internship.

The objective of this task is to clean and preprocess the Telco Customer Churn dataset using Python and Pandas.

## Dataset

The dataset contains customer information such as:

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Internet Service
- Contract
- Monthly Charges
- Total Charges
- Churn

## Data Cleaning Steps

The following preprocessing steps were performed:

1. Imported the dataset using Pandas.
2. Inspected the dataset structure and data types.
3. Checked for missing values.
4. Checked for duplicate records.
5. Identified the incorrect data type of `TotalCharges`.
6. Converted `TotalCharges` from object to numeric.
7. Identified 11 blank values in `TotalCharges`.
8. Handled the missing `TotalCharges` values.
9. Checked categorical values for consistency.
10. Saved the cleaned dataset as a new CSV file.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Files

- `CODSOFT_Task1_Data_Cleaning.ipynb` - Complete analysis and preprocessing
- `cleaned_telco_customer_churn.csv` - Cleaned dataset
- `data/` - Original dataset

## Conclusion

The dataset was inspected and cleaned using Pandas. Duplicate records and missing values were checked, data types were corrected, and the cleaned dataset was exported for further analysis.