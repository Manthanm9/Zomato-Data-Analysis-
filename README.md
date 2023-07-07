# Zomato Data Analysis

This project involves analyzing the Zomato dataset to gain insights into the restaurant scene in Bengaluru. The dataset contains information about various restaurants, including their names, ratings, cuisines, locations, and more. The goal is to perform exploratory data analysis to understand the trends and patterns in the data.

## Table of Contents
- Introduction
- Technologies Used
- Data
- Data Cleaning
- Exploratory Data Analysis
- Conclusion
- Function for Restaurant Suggestions
  
## Introduction
In this project, we analyze the Zomato dataset to gain insights into the restaurant landscape in Bengaluru. We perform data cleaning, visualization, and analysis to uncover interesting patterns and trends.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

The dataset used for this analysis is the "zomato_bengaluru.csv" file, which contains information about restaurants in Bengaluru, such as their names, online order availability, table booking options, ratings, votes, locations, cuisines, and more.

## Data Cleaning
Before analyzing the data, we perform data cleaning to handle missing values and remove unnecessary columns. We drop columns like URL, address, phone, menu items, and listing details as they are not required for our analysis.

## Exploratory Data Analysis
During the analysis, we explore various aspects of the dataset, including:

- Distribution of restaurant ratings
- Popular restaurant chains
- Online order acceptance rates
- Most-voted and best-rated restaurants
- Restaurant locations with the highest number of restaurants
- Favorite cuisines in Bengaluru
- The average cost for two people at different restaurants
## Conclusion
Based on our analysis, we draw the following conclusions:

- We identify the best-rated restaurants, such as Asia Kitchen By Mainland China and Punjab Grill.
- Cafe Coffee Day, Onesta, Empire Restaurant, Just Bake, and Kanti Sweets are among the top restaurant chains.
- Most restaurants (64.4%) accept online orders.
- The best-rated restaurants based on votes include Byg Brewski Brewing Company and The Black Pearl.
- The worst-rated restaurants based on votes include Lazeez and Tandoor Hut.
- BTM and Koramangala 5th Block have the highest number of restaurants.
- North Indian and Chinese cuisines are the most popular in Bengaluru.
- The average cost for two people at most restaurants ranges from 500 to 1000 rupees.

## Function for Restaurant Suggestions
We create a function that suggests a list of restaurants based on given parameters such as cost for two people, location, and restaurant type. For example, we find the names of restaurants in Whitefield for casual dining with a cost below Rs. 1000.
