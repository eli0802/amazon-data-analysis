
# Amazon Data Cleaning and Data Analysis Project
![Language](https://img.shields.io/badge/language-Python-l?style=square&color=%23002b4d)

####  Libraries:
- Pandas
- Matplotlib
- Numpy
- Scipy-stats
- Seaborn
- WordCloud
## Overview and Purpose:

A Data Analysis project of **Amazon** data from the **Electronics category** using **Python**, that will help you make better and more calculated decisions when buying products or selling products on Amazon India. The project will help buyers and sellers make **data driven decisions**, instead of relying on intuition or emoitions when doing market research. 

Amazon is a marketplace that has hundreds of thousands of listings, so the aim of this project is to help buyers filter out the products and choose the best, low-risk items, based on the brand, rating, rank, delivery type etc. It will help them find products efficiently, as this method of research will be less time-consuming.

## Questions answered with the analysis:
- Which are the top 10 brands in the sample you can focus on buying?
- Which is the preferred delivery type for the heavier products?
- Which are the top 20 SKUs/listings based on their rank, rating and selling price?
- Which are the top 20 sellers from the sample that may be considered as competition?

    - What is their preferred delivery type?
- Which are the most frequently used meta keywords in the sample? (useful when you want to create a new listing on Amazon)

## Data sources and the Data Cleaning process:
 Dataset - [Kaggle Amazon Electronics Dataset](https://www.kaggle.com/datasets/promptcloud/amazon-electronics-dataset-2020)

The Electronics dataset was collected from the Kaggle website. It contains a lot of dirty data, so the following operations need to be performed:

- Find and replace missing values
- Drop useless columns
- Convert the weight to a single measure - grams
- Set the correct data type for each column
- See how the data is distributed
- Detect and remove outliers with the Z-score statistical method
- Separate the data for more meaningful analysis


## Key Insights (see PDF Report for more):
1. The **Top 3 Sellers** prefer only **FBA as their shipping type**
2. Most of the seller in the top 20 have **between 50 and 75 products** on Amazon
   ![sellers](https://github.com/eli0802/amazon-data-analysis/assets/88452822/9a31ae28-3902-48d5-b77a-bd606e7c967f)

3. There’s a significant difference between the average rank of the light products listings that either have or don't have Amazon Prime
![prime_light](https://github.com/eli0802/amazon-data-analysis/assets/88452822/17049a46-7022-4586-880b-4565e7d02cf5)

4. 75% of the heavy products are sold on Amazon using the FBA delivery type
5. Top 20 Brands based on their Average Rating:
   ![brands_rating](https://github.com/eli0802/amazon-data-analysis/assets/88452822/5646fbbf-feeb-4515-9e24-3e7d08e93bfd)

6. Majority of the products are **Phone Cases or other phone accessories**

- That will explain why almost all of the products in the Electronics dataset are **light and have very low prices**

    ![wordcloud](https://github.com/eli0802/amazon-data-analysis/assets/88452822/703c4999-7815-4653-9616-65dc89f640af)
