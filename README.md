# DSND_blog
project for Udacity's DataScience NanoDegree program

This repository contains the deliverables for the assignment "Write a Data Science Blog Post" of Udacity's DataScience NanoDegree program.
I sincerely hope others may find the topic and techniques discussed helpful.

# Libraries used
The libraries used are:

matplotlib         2.1.2     
numpy              1.14.5    
pandas             0.23.1    
scikit-learn       0.20.3    
scipy              1.2.1     
seaborn            0.8.1     
sklearn-pandas     1.8.0     
Please pay attention especially to the version of scikit-learn due to changes in the library's organization

# Motivation
In this project the online shopping data from Instacart [1] is analyzed. In particular, the users are segmented into clusters (frequent and unfrequent users) and descriptive statistics is used to answer relevant business questions such as:

1. Do frequent users order in different days than infrequent users?
2. Do frequent frequent users order at different hours in the day than infrequent users?
3. How often do frequent users place orders compared to infrequent users?

# Files
The project requires the dataset from [1]. The files cannot be distributed on github but can be obtained from [1] or [2]. The archive file is unzipped in the current directory and comprises of several csv files. The description of the data files can be obtained at [2].

The files I uploaded are:

online_shopping_analysis.ipynb
Jupyter notebook with the full data analysis, data wrangling functions and comments.

online_shopping_analysis.html
HTML version of the above notebook

The blog post is available at: https://medium.com/p/139d0678fe03

# Summary of results
This analysis, based on descriptive statistics shows that there are different groups of users:

* frequent users order more during the week and the morning. They also order more often (within 7 days of the previous order)
* infrequent users order more on evening and weekends and tend to order every week or so

We note that this analysis was possible because of the very large dataset (3.4 orders with 200k individual users).
# Acknowledgements
This project makes use of the dataset: “The Instacart Online Grocery Shopping Dataset 2017”, Accessed from https://www.instacart.com/datasets/grocery-shopping-2017 on 2019-04-01.
The dataset is also available on Kaggle [2]




[1] https://www.instacart.com/datasets/grocery-shopping-2017
[2] [Kaggle Instacart competition](https://www.kaggle.com/c/instacart-market-basket-analysis)
[3] https://www.statsmodels.org/dev/generated/statsmodels.stats.proportion.multinomial_proportions_confint.html

