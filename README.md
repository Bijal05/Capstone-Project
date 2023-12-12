![E-Commerce Sales Prediction](images/kc_house_analysis.png)
#  Regression modeling to analyze E-Commerce Sales Prediction for Bespoke Aquariums

**Author**: Bijal Saija

## Overview

The dataset used in this analysis is sourced from the Bespoke Aquariums online store, capturing transactions between 01/05/2020 and 09/12/2023 for a Sydney-based and registered bespoke online retailer specializing in aquarium products.

The key business problem identified for stock maintenance and to keep the money flow controlled. Accurate sales forecasts are crucial for effective management in an e-commerce business. This project focuses on predicting sales for an online retail store, specifically Bespoke Aquariums, using data from actual transactions. Accurate sales forecasts enable retailers to more precisely plan for the future of an e-commerce business. Sales forecasting is an important part of meeting customer expectations and provides insight into how the market will react to any given product.

***

## Data

The data used in this analysis is taken from Bespoke Aquariums online store dataset "Data |bespoke_data Actual transactions of Sydney retailer ".
As with most real-world data sets, the column names were not perfectly described, so have done some research and I have used only those columns that affect sales. 

So after deciding what feature from the dataset to use and how to use it. The selected features are as below:
InvoiceNo
StockCode
Description
Quantity         
InvoiceDate      
UnitPrice      
CustomerID      
State           


## Methods

The project follows a data science lifecycle, encompassing data exploration, preprocessing, model development, and evaluation. The choice of algorithms, feature engineering techniques, and evaluation metrics will be explained in detail. Using one hot encoding technique created dummies for categorical variables to predict the sales more precisely. Used a bucketing technique to check how many items are selling together per order as well as what range of products are selling most. Also analyzed was the percentage of orders coming from outside of the state.

***
After checking the plot of each column there were so many outliers, that I decided to remove them as they can misguide the model to work properly. 

Developed a predictive model that estimates the impact of different types of marketing techniques and sales effects over time in business sales.
It identified and analyzed relevant features within the dataset that significantly contribute to the estimated sales value.
***

## Results

Predictive Model: Using a trained model predicted sales trends for future sales.
Recommendation System: Using the top-selling product list we can focus on stocking them.

Documentation: Comprehensive documentation detailing the methodology, code structure, and explanations of key decisions made during the project.


***

***



## Conclusions

Sales prediction is an ongoing challenge in the dynamic world of e-commerce. By leveraging historical data, and machine learning models, and considering various factors, this project aims to provide insights that can drive informed decision-making for the Bespoke Aquariums online retail business.

R-Squared - 0.948

Questions to consider:
Further analysis may include checking for model assumptions and exploring the residuals in more detail.
***


## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                                                <- The top-level README for reviewers of this project
├── predicting-sales-bespoke.ipynb                           <- Narrative documentation of analysis in Jupyter notebook
├── capstone_project.pdf                                     <- PDF version of project presentation
├── data                                                     <- Data repositories sourced externally
└── images                                                   <- Both sourced externally and generated from code
```
