# airtravel-data-cleaning
Data cleaning project using Pandas (Air Travel Dataset 1958–1960).

1. Overview

This project demonstrates a complete data cleaning workflow using Python and Pandas.
The dataset contains monthly passenger numbers for years 1958–1960.

2. Skills Demonstrated

Data loading & inspection

Handling missing values

Cleaning column names

Converting date formats

Transforming data from wide → long format

Sorting by categorical order

Exporting cleaned datasets

3. Project Files

airtravel_cleaning.ipynb — main cleaning notebook

airtravel.csv — raw dataset

cleaned_airtravel.csv — cleaned output

4. Data Cleaning Steps

Loaded data and inspected structure

Fixed column names (removed extra quotes)

Converted month abbreviations (JAN → January)

Transformed data using melt()

Sorted months in correct chronological order

Exported cleaned dataset

5. Final Cleaned Dataset Columns

Month (January–December)

Year (1958, 1959, 1960)

Passengers (numeric)

6. Conclusion

This project highlights essential data cleaning skills and prepares the dataset for time-series analysis or visualization.
