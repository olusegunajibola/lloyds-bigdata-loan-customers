# (Dataset Exploration Title)
## by (Olusegun Emmanuel Ajibola)


## Dataset


This document explores a dataset containing outcomes and attributes for approximately 18,000 loan application. Our objective is to understand and summarise the different behaviours or attributes between customers who paid back their loan and customers who did not using the historical data available. The data was gotten from Lloyd's Bank Big Data Challenge. Before cleaning, we had a dataset which comprised of 18324 records and 31 features. After data cleaning, we arrived at a 15863 by 28 dataframe.

### Data Wrangling

We had two variables whose missing values accounted for 50% of the data, as a result, we had to drop these columns entirely. Furthermore, for the variable that refers to missed payment, we filled its mssing values with zero. Furthermore, we removed double spaces from the data and converted required columns to categories (ordered and unordered). 


## Summary of Findings

Out of this 28 variables, we explored 21 variables to a univariate level and try to get insight as to how they affect a customer loan status (our variable of interest). After this, we investigated how a customer is ability to pay back their loans is affected by demography such as customer address state and other variables such as employment length, previous missed payments. We discovered that individuals that had 10+ years took more loans and paid back the most loans. Also, those who had less missed payments were able to pay back too. Furthermore, we noticed that many of the loan undertakers came from few states and there are good pay off behaviours in these states.


## Key Insights for Presentation

Using a multivariate plot, we saw how the combination of interest rate and employment length affects the ability to pay back and we discovered that those customers who were able to fulfil their obligations had lesser interest rates than the customers who were charged off and this remain fairly the same across all the 11 scales of employment years. We also performed a multivariate analysis in with loan status, average income and loan term and we concluded that those with more annual income were able to pay back their loans on both terms (36 months and 60 months).