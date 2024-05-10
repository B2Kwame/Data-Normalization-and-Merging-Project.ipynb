# Data-Normalization-and-Merging-Project.ipynb
# Data Normalization and Merging Project
# Overview
This project involves merging multiple datasets from different Excel and CSV files using pandas in Python. The aim is to normalize and merge data based on names, which are processed to ignore case and order discrepancies.

# Installation
To run this project, you need to install the required libraries. You can do this by running the following command:
pip install pandas openpyxl
# Usage
# The script performs several key operations:

# Loading Data
Data is loaded from multiple sheets of an Excel file and a single CSV file.
# Normalizing Names
Names are normalized to facilitate accurate merging.
# Merging Data
Data from different sources are merged based on the normalized names.
# Output
The output of this script includes:

A new Excel file common_data_output.xlsx that contains the merged data.
Console outputs that provide a preview of the merged data and the count of common entries.
# Conclusion
This script is particularly useful for data cleaning and preparation phases of data analysis projects, where merging data from multiple sources is a common requirement. The normalization of names ensures that the merging process is robust against common data entry variations.
