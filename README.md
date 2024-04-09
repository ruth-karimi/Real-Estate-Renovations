# Phase 1 Microsoft Movie Studio Project
Author: Ruth Nyakio

## Overview
Multiple linear regression of Northwestern County real estate sales data reveal opportunities for home owners to renovate houses and  increase their property values:
* Upgrade the sizes of the living and increase number of bedrooms and bathrooms
* Entire house renovations are encouraged than partial renovations.
* Improve overall condition of the house by regular maintenance.

## Business Problem
Finsco Limited, a real estate group investing in USA real estate has opened a consultancy arm. for their first project, they would like to understand how home renovations might increase the estimated value of homes, and by what amount.
The goal is to get insights to provide advice to homeowners, real estate investors and clients who do house-flipping
They have tasked the Hepta Group to conduct multiple linear regression modelling to analyze house sales in a Northwestern County they have been provided with.

## Data
* Data provided was King County House Sales data collected from 2014 and 2015.
* The target variable from this dataset is the property prices.
* Main factors affecting the price are sqft_living, bathrooms, bedrooms, condition, sqft_lot, floors and year_blt
* There were 21,597 records

## Methods
* Data cleaning: Handling duplicates, missing, null values  and encoding categorical variables
* Data visualization: Heatmaps, Histograms, Tableau, scatter plots and linear regression models 
* Simple Regression: Predicting price variable using one independent variable e.g. sqft_living, bathrooms , bedrooms  (Baseline Model)
* Multiple Regression: Used to predict our price using two or more independent variables e.g. sqft_living, bathrooms, bedrooms
   
## Results
* Increase in living area size increases property price. For 1 additional square feet, the home value increases by USD 279


* Properties with more bedrooms, have a higher price. Clients prefer 3 to 6 bedrooms. 1 additional bathroom, can increase the property price by USD 121,794

* More bathrooms increase house prices. 1 additional bathroom, can increase the price by USD 250,000

* A well maintained house will have more value. Improving house maintenance can increase the property value by USD 21, 460

* Houses built around 1930 and in the 21’st century have a high sale value


* Living room size, bathrooms and bedrooms have the highest effect on the value of the homes. The year the house was built and overall condition of the house have the least effect on the price



## Conclusions
* From the analysis and model summary,it  can be concluded that the proposed multiple linear regression model can effectively analyze and predict the housing price. 
* Overall house improvements will have a better impact on the value of the property than just renovating part of the house


## Recommendations
* Increase the size of the living room (sqfit_living). Bigger living spaces attract high prices.
* Upgrading bedrooms. Investing in bedroom renovations, will  increase the value of the property.
* Good house maintenance will improve the value of the homes. Home owners should ensure their homes rated average and above to improve the home value
* Bathroom is a minimum requirement and significant item in determining the home value. Assumption is that “advanced” / “more’ bathrooms attract higher prices


## Links to project resources
* Presentation - 
* Code - 
* Data -
* Tableau - https://public.tableau.com/views/KingCountySalesDashboard-Group8/KingCountySalesdashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link
* Column Description - https://github.com/learn-co-curriculum/dsc-phase-2-project-v2-3/blob/main/data/column_names.md

## Repository Structure
* 
