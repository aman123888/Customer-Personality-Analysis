# Customer-Personality-Analysis
Cleaning and preparing a customer marketing dataset for analysis
# Customer Personality Analysis – Data Cleaning

This repository contains the cleaned version of the **Customer Personality Analysis** dataset from a marketing campaign database.

##  Dataset Overview

The dataset contains information such as:
- Customer demographics (age, income, marital status, etc.)
- Product spending in different categories
- Responses to marketing campaigns

##  Data Cleaning Steps

Performed the following steps using Excel and/or Python:

1. **Removed Duplicates**  
   - Verified there are no duplicate `ID`s in the dataset.

2. **Handled Missing Values**  
   - Checked for blanks in columns like `Income` and filled them with the median where appropriate.

3. **Standardized Text Values**  
   - Cleaned inconsistent labels in `Marital_Status` and `Education`.
   - Made all text lowercase and removed extra spaces.

4. **Formatted Dates**  
   - Converted `Dt_Customer` to proper `dd-mm-yyyy` format.

5. **Renamed Columns**  
   - Changed all column headers to lowercase with underscores for consistency.

6. **Checked & Fixed Data Types**  
   - Ensured numeric fields like `Income` and `Recency` are numbers.
   - Verified `Dt_Customer` is in proper date format.

##  Files Included

- `cleaned_marketing_campaign.csv`: Cleaned dataset
- `data_cleaning_notes.md`: Explanation of the steps taken

##  Future Work

- Exploratory data analysis
- Customer segmentation
- Predictive modeling
