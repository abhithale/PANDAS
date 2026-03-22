#BigBasket Product Analysis with Pandas
This repository contains a Jupyter Notebook (Pandas.ipynb) dedicated to practicing data manipulation and exploratory data analysis (EDA) using the Pandas and NumPy libraries.

📁 Dataset Overview
The analysis is performed on a BigBasket Products dataset, which includes:

Total Records: 27,555 products.

Features: index, product name, category, sub-category, brand, sale price, market price, type, rating, and description.

🛠️ Concepts & Techniques Practiced
1. Data Exploration
Initial Inspection: Used .head(), .tail(), and .shape to understand the data's dimensions and first/last entries.

Metadata & Statistics: Leveraged .info() to check data types and memory usage, and .describe() to generate summary statistics for numerical columns like sale_price and rating.

Selection: Practiced selecting specific columns and filtering for specific brands (e.g., filtering for Nivea products).

2. Data Cleaning & Handling Missing Values
Null Identification: Used .isnull().sum() to identify missing data in the rating and description columns.

Handling Missing Data: Practiced different techniques for dealing with NaN values:

Dropping: Using .dropna() to remove incomplete rows or columns.

Imputation: Using Forward Fill (ffill) and Backward Fill (bfill) to fill gaps in the dataset.

3. Data Manipulation
Sorting: Ordered products by sale_price to identify the cheapest and most expensive items.

Renaming: Practiced modifying column names for better readability using .rename().

Advanced Indexing: Implemented loc[] and iloc[] for label-based and integer-based data retrieval.

💻 Tech Stack
Language: Python 3

Libraries: Pandas, NumPy
