# Quantium Virtual Internship: Project Overview
Undertook data preparation, customer analytics, experimentation, uplift testing, performance analytics and commercial application for a large dataset from a major supermarket franchise.

- Undertook data cleaning, transformation and preparation of a large sample dataset from a major retailer

- Undertook customer analytics to derive insights into customer spending behaviour and high performing products

- Developed a strategy for the spending manager to implement, which would optimise slaes for specific product categories 

- Created a measure to compare different control stores against stores which had recently trialled new layouts

- Used the most suitable control store to benchark performance and used performance analytics to assess the impact of new layouts in trial stores

## Resources

**Python Version:** 3.7

**Packages:** pandas, numpy, matplotlib, seaborn

**Project Basis:** Virtual Internship with Quantium - project completed as a task for the Quantium Virtual Internship 

## Data Preparation and Customer Analytics

 This consisted of the following stages:

- Examined transaction data looking for inconsistencies, missing data and outliers

- Cleaned the data using ordinal mapping and filling of missing values and outliers with statistical best fit values

- Merged customer data with transaction data to create a unified sales dataset

- Defined performance metrics and identified total sales, drivers of sales and highest performing products

- Conducted a deep dive into customer segments to advise which segments should be targeted.  

## Experimentation and Uplift Testing



## Model Building

First, I transformed the data structure into a dataframe and produced dummy variables where applicable. I used train_test_split to split the data into train (80%) and test (20%) sets.  

I developed three models and used GridSearchCV to optimsie the model parameters, using Mean Absolute Error (MAE) as the evaluation criteria. 

The models were:
- **Multiple Linear Regression**
- **Lasso Regression**
- **Random Forest**

## Model Performance

All of the models performed relatively well and were able to predict the final points total of the football club within +- 3 points. 
The Random Forest model was the best performing of the three models.

- **Multiple Linear Regression:** MAE = 4.19
- **Lasso Regression:** MAE = 4.23
- **Random Forest:** MAE = 4.16
 
 ## Productionisation
 
 In this stage, I made a Flask API web server following along with the TDS Tutorial and Ken Jee Data Science Project Video in the reference section above. The API takes a list of input values and returns the estimated position of the football team in the league at the end of the season.
 
 Projected values can be input into the model throughout the season to predict the final points total of the football team in the league. 
 
 




