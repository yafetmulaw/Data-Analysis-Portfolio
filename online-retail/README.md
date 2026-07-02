# Online Retail Transaction Analysis

This project analyzes transactional retail data to understand customer purchasing behavior and product relationships. The focus is on invoice-level transactions, product frequency, and identifying items that are frequently bought together using market basket analysis techniques.

The dataset represents real-world e-commerce activity, including invoices, product descriptions, quantities, and customer interactions.

## Key Insights

* **Transaction Patterns**: Customer purchases are structured around multi-item invoices, enabling analysis of product combinations.
* **Top Products**: A small number of products appear frequently across transactions, indicating high demand.
* **Product Associations**:

  * Certain product pairs are consistently purchased together.
  * These combinations suggest strong opportunities for bundling and cross-selling.
* **Customer Behavior**:

  * Repeated purchase patterns exist across invoices.
  * Purchasing behavior shows consistency in item groupings.
* **Performance Consideration**:

  * Large dataset required sampling for efficient computation during basket analysis.

## Techniques Applied

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Transaction-Level Analysis
* Market Basket Analysis (Association Analysis)
* Frequency Analysis
* Sampling / Performance Optimization

## Files in This Folder

* **Script1.ipynb** → Main analysis notebook (data cleaning, transformation, and analysis)
* **Dataset** → the actual dataset with over 1M+ rows

## Data Sources

* Online Retail II dataset (transactional e-commerce data)
* Analysis performed using Python (Pandas, NumPy) in Jupyter Notebook

## How to Use / Replicate

1. Open **Script1.ipynb** in Jupyter Notebook.
2. Load the dataset into your working directory.
3. Run the notebook step-by-step:

   * Data cleaning and preprocessing
   * Transaction grouping by invoice
   * Product combination generation using `combinations`
   * Frequency counting using `Counter`
4. Modify sampling size if working with limited computational resources.

Feel free to reach out for questions!

Yafet Mulaw  
Addis Ababa, Ethiopia  
Email: yafetmulaw@gmail.com  
[Yafet Mulaw on LinkedIn](https://www.linkedin.com/in/yafet-mulaw/)
