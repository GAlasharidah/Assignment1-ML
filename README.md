# Assignment 1 - Dataset Description

## Dataset Name
Snitch Fashion Sales Dataset (Uncleaned)

## Dataset Source
This dataset was **provided as a user-uploaded file for academic EDA practice**.  
Because no verified public source link was included with the file, it is described here as a **user-provided fashion sales dataset**.

## Number of Rows and Columns
- **Rows:** 2500
- **Columns:** 12

## Features (Columns) Description

| Column | Description |
|---|---|
| `Order_ID` | Unique or semi-unique identifier for each order record. |
| `Customer_Name` | Name of the customer associated with the order. |
| `Product_Category` | High-level category of the product such as T-Shirts, Dresses, Jackets, etc. |
| `Product_Name` | Specific product item name. |
| `Units_Sold` | Quantity of units sold in the order. |
| `Unit_Price` | Price of one unit of the product. |
| `Discount_%` | Discount value applied to the order. In this dataset, it behaves like a decimal discount rate. |
| `Sales_Amount` | Total sales amount for the order. |
| `Order_Date` | Date when the order was placed. |
| `City` | City associated with the sale or customer. |
| `Segment` | Customer segment, such as B2B or B2C. |
| `Profit` | Profit value associated with the transaction. |

## Purpose of Using This Dataset
This dataset was chosen because it contains several realistic data quality issues that make it suitable for **Exploratory Data Analysis (EDA)** and **data cleaning practice**.  
Examples of these issues include:
- missing values
- repeated `Order_ID` values
- inconsistent city names
- mixed date formats
- invalid numeric values
- suspicious sales values

These characteristics make the dataset useful for applying EDA techniques such as:
- data inspection
- data cleaning
- feature understanding
- visualization
- insight generation

## Files Included in Assignment 1 Folder
- `Snitch_Fashion_Sales_Uncleaned.csv` → original dataset
- `Snitch_Fashion_Sales_Cleaned.csv` → cleaned dataset used for analysis
- `Snitch_Fashion_Sales_EDA.ipynb` → full EDA notebook
- `README.md` → dataset description file



Assignment1 - Ghala Alsharidah
2026 