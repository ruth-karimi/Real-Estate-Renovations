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
<img width="489" alt="image" src="https://github.com/ruth-karimi/Real-Estate-Renovations/assets/24277899/52f41268-a99a-4e4c-8b29-be0d247a2d78">

* Properties with more bedrooms, have a higher price. Clients prefer 3 to 6 bedrooms. 1 additional bathroom, can increase the property price by USD 121,794
<img width="578" alt="image" src="https://github.com/ruth-karimi/Real-Estate-Renovations/assets/24277899/9733b524-9e60-4d0e-8790-8489ee646a27">

* More bathrooms increase house prices. 1 additional bathroom, can increase the price by USD 250,000
<img width="578" alt="image" src="https://github.com/ruth-karimi/Real-Estate-Renovations/assets/24277899/079782a5-90a3-4268-91d0-be47e125bc16">

* A well maintained house will have more value. Improving house maintenance can increase the property value by USD 21, 460
<img width="578" alt="image" src="https://github.com/ruth-karimi/Real-Estate-Renovations/assets/24277899/c98ed892-abb7-4232-a521-4052dc1e2b0e">

* Houses built around 1930 and in the 21’st century have a high sale value
<img width="708" alt="image" src="https://github.com/ruth-karimi/Real-Estate-Renovations/assets/24277899/ef77f646-ffea-44e9-b5cb-b29ab6eebdda">

* Living room size, bathrooms and bedrooms have the highest effect on the value of the homes. The year the house was built and overall condition of the house have the least effect on the price
<img width="578" alt="image" src="https://github.com/ruth-karimi/Real-Estate-Renovations/assets/24277899/50c3b6f2-9439-4003-9620-061ffb519ea0">

## Conclusions
* From the analysis and model summary,it  can be concluded that the proposed multiple linear regression model can effectively analyze and predict the housing price. 
* Overall house improvements will have a better impact on the value of the property than just renovating part of the house

## Recommendations
* Increase the size of the living room (sqfit_living). Bigger living spaces attract high prices.
* Upgrading bedrooms. Investing in bedroom renovations, will  increase the value of the property.
* Good house maintenance will improve the value of the homes. Home owners should ensure their homes rated average and above to improve the home value
* Bathroom is a minimum requirement and significant item in determining the home value. Assumption is that “advanced” / “more’ bathrooms attract higher prices

## Links to project resources
* Presentation - https://github.com/ruth-karimi/Real-Estate-Renovations/blob/main/Real%20Estate%20Renovation%20Presentation.pdf
* Code - https://github.com/ruth-karimi/Real-Estate-Renovations/blob/main/Phase_2_Project.ipynb
* Data - https://github.com/ruth-karimi/Real-Estate-Renovations/blob/main/kc_house_data.csv
* Tableau - https://public.tableau.com/views/KingCountySalesDashboard-Group8/KingCountySalesdashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link
* Column Description - https://github.com/learn-co-curriculum/dsc-phase-2-project-v2-3/blob/main/data/column_names.md

## Repository Structure
<img width="332" alt="image" src="https://github.com/ruth-karimi/Real-Estate-Renovations/assets/24277899/f59c8eb3-42e1-472c-a6d0-25912326997e">
