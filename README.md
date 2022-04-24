# Customer Segment Analysis
## Introduction
- Advertising on the whole population can be costly and ineffective

## Contributors
- Twu Pin Yang - Data Preparation and Exploratory Analysis
- Marco Nathaniel Lu Ng - Decision Tree Models and Data Insights
- @yungchu123 - K Means Clustering and Conclusion

## Problem Definition
- Choose a target customer segment for marketing campaign in order to reduce costs and maximise profits
- Specific Product Chosen: Wine

## Data Preparation
- Remove NaN values in Income column
- Replace illogical values (e.g. Alone, Absurd) in Marital_Status with 'Single'
- Remove outliers 
- Create new Age column from Year_Birth
- Create KidsPresent column (Boolean) from Kidhome 

## Models Used
1. Decision Tree Classifier
2. K Means Clustering

## Findings
- Households with higher income tend to spend more on wine
- Households with kids at home tend to spend less on wine
- Also, K Means Clustering can help us to split customers into different segments better

## Conclusion
- Thus, our recommendation is to target wine marketing specifically on households with high income and no kids at home.
 
 ## References
 - https://www.kaggle.com/code/willianhaeberlin/naive-bayes-classification/notebook
 - https://www.analyticsvidhya.com/blog/2019/08/comprehensive-guide-k-means-clustering/

