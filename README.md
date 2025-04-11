
# Can We Predict Life Expectancy Using Machine Learning?

Exploring Machine Learning Techniques using Health and Economic data from the World Bank Databank.

## Installation

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.


## Project Motivation

For this project I was interested in investigating if we can predict the life expectancy of a country based on a number of health and economic factors.

More specifically, I will try to answer :

    1. What is the impact of the below features with regards to life expectancy?
         
         * Fertility rate, total (births per woman) 
         * Total greenhouse gas emissions
         * Current health expenditure per capita
         * People using at least basic drinking water services (% of population)

    2. What is the relationship type of each feature with my dependent variable (Life Expectancy)?

    3. Which of the above variables should be included in our Machine Learning models?
    4. Which model generates the most promising results and can be used in a real world scenario?

## File Descriptions

The repository contains a jupyter notebook with the below structure:

*Please note that raw data was stored in Google drive so that the notebook can run without having to download the excel file locally.
      
      Section 1 EDA
        * Generate descriptive statistics
        * Generate histograms to visualize data distributions
        * Generate boxplots to check for outliers
        * Generate scatter plots to visualize the relationship of the independent variables with the dependent
        * Generate correlation table to check the potential impact of each independent variable with the dependent
      
     Section 2 Data preprocessing
        * Check and handle missing values
        * Check and handle outliers
        * Check and handle data types
        * Add and/or drop columns
        * Decide which features to include in our models

    Section 3 Predictive Modelling
        * Split the data into a Training and a Test set
        * Train and assess the accuracy of a Linear Regression, a Decision Tree and a Random Forest model.

    Section 4 Conclusion and results
        * Summarize the results of the train models and showcase a scenario under which they could be used.
        
## Results

    My methodology and my summarized main findigs can be found at the below post.

    https://medium.com/@leandrosnikolopoulos/can-we-predict-life-expectancy-using-machine-learning-239b83d8d29d

## Licensing, Authors, Acknowledgements
    All data has been extracted from the World Bank Databank Website.
