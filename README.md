# Module 1 Final Project - King county dataset analysis

## Name and delegation:
- Joe - Question 1
- Laura - Question 2
- Shuyu - Question 3

## Overview
The king county housing market is highly competitive, and we want to be the best real estate agent advisor in the area. To compete with our peers, we decide to leverage a few basic machine learning concepts to assist us and a client with finding the best selling price for their home. Luckily, we’ve come across the King County Housing data set which contains aggregated data on various features for houses in Greater Seattle communities. Our task is to build an optimal model based on a statistical analysis with the tools available. This model will then used to estimate the best selling price for our client’s home.

## Install
This project requires Python 3 and the following Python libraries installed:

- NumPy
- Pandas
- Seaborn
- statsmodels.api
- scikit.learn
- scipy
- geopandas
- descartes

## Data
kc_house_dataset.csv

## Deliverables:
- jupyter notebook
- powerpoint slides

## Methodology and findings
We used linear regression models to fit with our dataset from three angles:
- Internal features of property
- Geographic features of property
- Zipcode of property

From the analysis of internal features angle, we find housing grade system and square foot area expect basement have stronger impacts on housing price, and instead of looking into various internal housing features, we suggest the property agency just focus on few of them (e.g. ignore square foot per living as it already shows in other features)
<br>
<br>
From the analysis of geographic angle, features affecting the pricing of square footage are: waterfront, and latitudinal and longitudinal coordinates. The closer to water bodies, the higher the price.More research must be carried out in order to find the best value for money, regarding square footage of living areas without comprimising with premium features
<br>
<br>
From the analysis of zipcode angle, we compared many variables against housing price, and came to the conclusion that square footage of the property had a close relationship to the Price. I then decided to look at how price and square footage of the property compared to each other in zip codes that had a high average house price. This showed that square footage of the property had an even closer relationship with price when looking specifically at high priced zip codes. From this we can conclude, that the size of a house has a bigger affect on the price of a house in high priced zip codes than other zip codes.