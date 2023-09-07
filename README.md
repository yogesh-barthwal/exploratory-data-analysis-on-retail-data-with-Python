# exploratory-data-analysis-on-retail-data-with-Python
This project contains a detailed exploratory data analysis on an online retail  store data using Python
The dataset, "Online Retail" dataset contains transactional data of an online retail store from 2010 to 2011
Operations perfrpmed include-
  - Data Cleaning
    - Verifying the data types of features and making corrections if unsuitable types are detected
    - Checking for and dropping the duplicates
    - Checking fro null values
    - Dropping entries containing values less than one for quantity from the main dataframe and storing them in a different dataframe as returns
    - Dropping entries containing zero or negative values aginst price. These probably indicate discounts or prodcts offered as free of cost with some other products
    - Dropping features that would not add to analysis
  - Adding a new feature Sales as a product of Unit Price and Quantity
  - Analysing summary of the dataset
  - Performing univariate and bivariate analysis by creating visualizations to understand the data better
    - Creating a visualization for the top 10 countries with the highest sum of sales (excluding UK- UK being much higher than the rest)
    - Creating a visualization for the 10 countries with the least sum of sales
    - Creating a visualization for top 10 countries by Quantity sold (excluding UK- UK being much higher than the rest)
    - Creating a visualization to identify 10 best and 10 worst selling products
    - Creating a visualization to observe month wise Sales
    - Creating a visualization to identify top 10 customers by amount of sum of sales
  - Final Inferences on the basis of analysis

  
