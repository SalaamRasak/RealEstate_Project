# Real Estate Dataset Analysis: King County House Sales

## Project Overview
This project focuses on wrangling and analyzing real estate datasets, specifically examining house sales in King County, USA. The goal is to explore patterns in the housing market, utilizing Python libraries and statistical correlation and regression to derive insights. 

## Frameworks and Libraries Used
The Python libraries I used include:
- **Pandas** for data manipulation and cleaning.
- **Numpy** for handling numerical data and performing calculations.
- **Seaborn** for creating visualizations for statistical graphics.
- **Matplotlib** for data visualization plotting.
- **Scikit-learn** for implementing machine learning models, including Ridge Regression.

## Dataset Description
The dataset consists of house sales in King County, USA, containing details like the house's price, location, number of bedrooms, and more. The project involves analyzing these features to build a predictive model for house prices.

## Key Features of the Project
- Data were wrangled, cleaned, and an overview were derived using pandas
![Data Summary](/Images/Screenshot%202025-10-07%20215015.png)

- I used boxplot in the seaborn library to determine whether houses with a waterfront view or without a waterfront view have more price outliers
<img src="/Images/Screenshot%202025-10-07%20215113.png" alt="Box Plot" width="500" height=auto/>

- I used the function regplot in the seaborn library to determine if the feature sqft_above is negatively or positively correlated with price.
<img src="/Images/Screenshot%202025-10-07%20215149.png" alt="Box Plot" width="500" height=auto/>

- I applied Pandas method corr() to find the degree of correlation between other features of the houses vis-a-vis price.
![Degree of correlation](/Images/Screenshot%202025-10-07%20215215.png)

- I used linear regression model to predict the 'price' using the feature 'sqft_living' then calculate the R^2. 
![Code Snipper](/Images/Screenshot%202025-10-07%20215304.png)

