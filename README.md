# Excel Data Cleaning & Analysis Tool

A simple tool to clean and analyze Excel files using Python.

## Quick Start


# 1. Install required libraries
pip install pandas openpyxl matplotlib numpy

# 2. Create sample data
python create_sample_data.py

# 3. Run the tool
python excel_data_tool.py
Main Features (2 Lines Each)
Feature	What it does
Load Excel	Reads any .xlsx file and shows preview of data
Clean Data	Removes duplicate rows and fills missing values automatically
Analyze Data	Shows average, min, max values and groups data by category
Filter Data	Finds specific values or applies conditions like "Age > 30"
Create Charts	Makes graphs (histograms, bar charts) from your data
Save Results	Saves cleaned data as Excel/CSV + generates summary report
Important Pandas Concepts
Term	Simple Meaning
DataFrame	Your Excel sheet stored in Python
.drop_duplicates()	Removes duplicate rows
.fillna()	Fills empty cells
.groupby()	Groups data (e.g., average salary by department)
.describe()	Shows all statistics at once
Files in Project
excel_data_tool.py - Main program (RUN THIS)

create_sample_data.py - Creates test data (RUN FIRST)

sample_data.xlsx - Your data file

Common Problems
Problem	Solution
"File not found"	Place Excel file in same folder as the tool
"No module named pandas"	Run pip install pandas
Can't load file	Make sure it's .xlsx or .xls format


Made with pandas 🐼


your-project-folder/
├── excel_data_tool.py
├── create_sample_data.py
├── sample_data.xlsx
└── README.md ← Create this here
