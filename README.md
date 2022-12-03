# Seattle-Data-Analysis-Journey
This Repository includes all files for the Seattle Data Analysis Jounrney

### Table of Contents

- [Libraries](#libraries)
- [Project motivation](#motivation)
- [Files](#files)
- [Results](#results)
- [Aknowledgements](#acknowledgements)

## Libraries<a name="libraries"></a>

The project is running with Python 3 and Jupyter Notebook.
The following libraries are used for the project:
- numpy
- pandas
- matplotlib 
- seaborn
- scikit-learn

## Project motivation <a name="motivation"></a>

I am still planning a trip to visit Seattle, maybe in 2023. Therefore I am going to start a seattle data analysis journey of available airbnb data to find an appropriate location. An appropriate location for me should be cheap and should meet the promising expectations. Therefore, in a first step I try to find the top 5 cheapest area's in seattle for a stay and in a second step I try to find a specific location with the best price-rating-ratio within the top 5 cheapest area's. The price-rating-ratio reflects the requirement to a location to meet the promising expectations. Last but not least I am interesting in what the top 5 influencing factors of price-rating-ratio are?

**Questions to answer:**   
1. What are the top 5 cheapest area's in general for a stay in seattle?
2. What are the top 5 location's with the best "price-rating-ratio" within the 5 cheapest area's?
3. What are the top 5 factors influencing the "price-rating-ratio"?


## File Descriptions<a name="description"></a>

The original dataset for Airbnb Seattle can be found on Kaggle: https://www.kaggle.com/datasets/airbnb/seattle?select=reviews.csv

`calendar.zip`:  
contains calendar.csv - data such as availability, dates, price for the upcoming year

`listings.zip`:  
contains listings.csv - every listing and has data such as bedrooms, bathrooms, host rating

`reviews.zip`:  
contains reviews.csv - unique id for each reviewer and detailed comments


## Results <a name="results"></a>

The results can be found in the blog post [here](https://www.kaggle.com/code/andreasschoch/seattle-data-analysis-journey-of-airbnb-data).

Summary of the three key findings:  

### Question 1: What are the top 5 cheapest area's in general for a stay in seattle?
### Answer:
1. Rainier Beach
2. Olympic Hills
3. North Delridge
4. Georgetown
5. Brighton

### Question 2: What are the top 5 location's with the best "price-rating-ratio" within the 5 cheapest area's?
### Answer:
1. 7902382
2. 8409926
3. 7902068
4. 7902268
5. 4639040

### Question 3: What are the top 5 factors influencing the "price-rating-ratio"?
### Answer:
1. accommodates
2. bathrooms
3. host_listings_count
4. minimum_nights
5. guests_included

This analysis was part of the Udacity Data Science Nanodegree.   

## Acknowledgements <a name="acknowledgements"></a>

The source for the data is Inside Airbnb which was imported to Kaggle [here](https://www.kaggle.com/datasets/airbnb/seattle) and is available under Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license.
