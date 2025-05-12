🛍️ Diwali Sales Data Analysis

This project performs exploratory data analysis (EDA) on Diwali sales data to derive customer insights and purchasing behavior trends. The goal is to assist business decision-making by identifying key demographics, product preferences, and regional demand patterns during the Diwali season.
📁 Dataset

    Source: Diwali Sales Data.csv

    Records: 11,251 entries

    Features: 15 columns including customer demographics, purchase information, and order details.

📊 Libraries Used

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline

🧹 Data Cleaning

    Dropped unrelated or empty columns: Status, unnamed1

    Removed 12 records with missing Amount values

    Converted Amount column from float64 to int64 for consistency

📈 Exploratory Data Analysis (EDA)
1. Gender-Based Analysis

    Majority of buyers are female

    Females have higher purchasing power compared to males

2. Age Group Analysis

    Most purchases are made by customers aged 26-35 years

    Females aged 26-35 are the top buyers

3. State-Wise Analysis

    Top 3 states by orders and revenue:
    Uttar Pradesh, Maharashtra, Karnataka

4. Marital Status

    Most purchases are made by married women

    Married women contribute significantly to overall sales

5. Occupation

    Top spending customers are from IT, Healthcare, and Aviation

6. Product Categories

    Most sold categories: Food, Clothing, Electronics

    Top 10 products by order volume are identified

📌 Key Insights

    Married women aged 26-35 years, primarily from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, or Aviation, are the most frequent and high-spending customers.

    Food, Clothing, and Electronics are the most popular categories during the Diwali season.
    
