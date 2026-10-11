# SWYNEX Data Cleaning and Basic Analysis

Task 2 of my internship with SWYNEX Technologies.

## Dataset
Titanic passenger dataset (891 rows, 12 columns).

## Tools
Python, Pandas, Matplotlib (Google Colab)

## Files
- `SWYNEX_Data_Cleaning_and_Basic_Analysis.ipynb`: full notebook
- `titanic_raw.csv`: original data
- `titanic_cleaned.csv`: cleaned data

## Cleaning Steps
- Removed duplicate rows (none found)
- Filled 177 missing Age values with the median
- Filled 2 missing Embarked values with the most common port
- Dropped the Cabin column (687 of 891 values missing)

## Key Findings
- 891 passengers; 342 survived (38.4%)
- Female survival rate was 74% versus 19% for males
- Survival by class: 63% (1st), 47% (2nd), 24% (3rd)
- Average age was 29.4 and average fare was 32.2

## Charts
Bar charts of survival by sex and class, plus an age distribution histogram.
