# Diwali Sales Analysis

Exploratory Data Analysis project on Diwali sales data to understand customer purchasing behavior and identify the most valuable customer segments, product categories, and regions.

## Project Objective

The objective of this analysis is to study Diwali sales transactions and generate business insights that can help improve customer targeting, inventory planning, and marketing strategy.

## Dataset

- File: `Diwali Sales Data.csv`
- Records after cleaning: `11,239`
- Key columns: `Gender`, `Age Group`, `Marital_Status`, `State`, `Zone`, `Occupation`, `Product_Category`, `Orders`, `Amount`

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Workflow

1. Imported required Python libraries.
2. Loaded the Diwali sales dataset.
3. Checked dataset shape, columns, data types, and missing values.
4. Removed blank or irrelevant columns such as `Status` and `unnamed1`.
5. Dropped missing values and converted `Amount` into integer format.
6. Performed univariate and bivariate analysis using count plots and bar charts.
7. Analyzed sales patterns by gender, age group, state, marital status, occupation, and product category.

## Key Insights

- Female customers placed more orders and showed higher purchasing power than male customers.
- The `26-35` age group contributed the highest number of buyers.
- Married women were one of the strongest customer segments.
- Uttar Pradesh, Maharashtra, and Karnataka generated the highest sales.
- Customers working in IT, Healthcare, and Aviation were the top contributors to sales.
- Food, Clothing & Apparel, and Electronics & Gadgets were the leading product categories.

## Business Conclusion

The most valuable customer segment is married women aged `26-35` from Uttar Pradesh, Maharashtra, and Karnataka, mainly working in IT, Healthcare, and Aviation sectors. These customers are more likely to purchase products from Food, Clothing & Apparel, and Electronics & Gadgets categories.

## How to Run

1. Clone this repository.
2. Open `Diwali_Sales_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Keep `Diwali Sales Data.csv` in the same project folder.
4. Run the notebook cells from top to bottom.

## Project Files

- `Diwali_Sales_Analysis.ipynb` - Main Jupyter Notebook containing the analysis.
- `README.md` - Project documentation.

