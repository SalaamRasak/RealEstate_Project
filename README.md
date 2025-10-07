# Real Estate Dataset Analysis: King County House Sales

## Project Overview
This project focuses on wrangling and analyzing real estate datasets, specifically examining house sales in King County, USA. The goal is to explore patterns in the housing market, utilizing Python libraries and statistical correlation and regression to derive insights. 

## Frameworks and Libraries 
The Python libraries used include:
- **Pandas** for data manipulation and cleaning.
- **Numpy** for handling numerical data and performing calculations.
- **Seaborn** for creating visualizations for statistical graphics.
- **Matplotlib** for data visualization plotting.
- **Scikit-learn** for implementing machine learning models, including Ridge Regression.

## Dataset Description
The dataset consists of house sales in King County, USA, containing details like the house's price, location, number of bedrooms, and more. The project involves analyzing these features to build a predictive model for house prices.

## Key Features of the Project
- The data was wrangled and cleaned, with an overview derived using pandas
![Data Summary](/Images/Screenshot%202025-10-07%20215015.png)

- A boxplot was created using the Seaborn library to determine whether houses with a waterfront view or without a waterfront view have more price outliers.
<img src="/Images/Screenshot%202025-10-07%20215113.png" alt="Box Plot" width="500" height=auto/>

- The regplot function from Seaborn library was used to determine if the feature sqft_above is negatively or positively correlated with price.
<img src="/Images/Screenshot%202025-10-07%20215149.png" alt="Box Plot" width="500" height=auto/>

- The pandas corr() method was applied to find the degree of correlation between the features of the houses in relation to the price.
![Degree of correlation](/Images/Screenshot%202025-10-07%20215215.png)

- A linear regression model was used to predict the 'price' using the feature 'sqft_living' followed by calculating the R^2 score. 
![Code Snipper](/Images/Screenshot%202025-10-07%20215304.png)

