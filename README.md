**Market Basket Optimization using FP-Growth
Overview**

This project performs Market Basket Analysis to find items that are frequently purchased together.
The FP-Growth algorithm is used because it is faster and more efficient than traditional methods like Apriori.

The notebook is designed to run in Google Colab.

**Objective**

Identify frequent item combinations

Generate association rules from transaction data

Analyze customer purchasing patterns

**Algorithm Used**

FP-Growth (Frequent Pattern Growth)

Does not generate candidate itemsets

Uses an FP-Tree for efficient processing

Suitable for large datasets

**Tools and Libraries**

Python

Google Colab

Pandas

mlxtend

**Dataset**

Each row represents one transaction

Each item in a row represents a product purchased

**Example:**

Milk,Bread,Butter
Bread,Diaper,Beer

**Steps Followed**

Load the dataset

Convert data into transaction format

Encode transactions

Apply FP-Growth

Generate association rules

Analyze results using support, confidence, and lift

**Output**

Frequent itemsets

Strong association rules showing item relationships

**Conclusion**

FP-Growth efficiently discovers useful buying patterns from transaction data.
The results can be used for recommendations, product placement, and sales strategies.
