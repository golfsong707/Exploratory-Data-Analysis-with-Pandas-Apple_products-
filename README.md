# Exploratory Data Analysis:Apple Products Dataset Analysis.
This repository contains Python code for analyzing Apple product data using the pandas library. 

The dataset used for this analysis is stored in a CSV file named apple_products.csv. 

The dataset contains information about various Apple products, including their product name, URL, brand, sale price, MRP (Maximum Retail Price), discount 

percentage, number of ratings, number of reviews, UPC (Universal Product Code), star rating, and RAM.

# Prerequisites
Python installed on your system

Required libraries: pandas

To run the analysis, make sure you have Python and the pandas library installed. You can install pandas using the following command:
pip install pandas

Place the apple_products.csv file in the same directory as the Jupyter Notebook or Python script that you'll use for analysis.

# Analysis Steps
Importing Data: The code begins by importing the pandas library and loading the dataset using the pd.read_csv() function.

Data Overview: The dataset is displayed using the df DataFrame to provide an initial view of the data.

# Basic Data Exploration:
The df.head() function is used to display the first five records of the dataset.

The df.tail() function is used to display the last five records of the dataset.

The df.count() function is used to check if there are any missing values in the dataset.

Descriptive Statistics: The df.describe() function provides descriptive statistics for the numerical columns in the dataset.

# Maximum and Minimum Prices:
The maximum price (MRP) of a product is calculated using df['Mrp'].max().

The minimum price (MRP) of a product is calculated using df['Mrp'].min().

# Products with Maximum and Minimum Sales:
Products with the maximum sales price are filtered using df[df['Mrp']==149900].

Products with the minimum sales price are filtered using df[df['Mrp']==39900].

Sorting by Star Rating: The dataset is sorted by the 'Star Rating' column in descending order using df.sort_values(by=['Star Rating'], ascending=False).

# Extracting Product Names:
The code extracts the 'Product Name' column from the DataFrame using df['Product Name'].

The extracted column is converted into a list named listed_col.

# Results
The analysis script provides insights into the dataset's characteristics, including statistics about prices, sales, and ratings. 

Additionally, it sorts the data based on star ratings and lists the product names.

# Running the Code
You can run the provided code in a Jupyter Notebook or any Python environment that supports pandas. 

Make sure to place the apple_products.csv file in the same directory as your code.

### Anungar note:
To further this analysis, additional analysis or visualization can be perform based on the new  requirements needed.
