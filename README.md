
# Airbnb Data Analysis

This repository contains code and analysis for an Airbnb dataset. The key contents are:

## Data

The `data/` folder contains the raw Airbnb dataset in CSV format.

## Notebooks

- `AIRBNB.ipynb`: Initial exploration and visualization ,Statistical hypothesis testing on several relationships and regression model to predict listing prices in the data


## Analysis

The main findings and results of the analysis are:

- Listing prices vary significantly based on the neighborhood/borough
- Listings with more reviews have higher prices 
- Listings described as "luxury" are priced higher than those described as "modern"
- A regression model can predict listing prices with an R-squared of 0.51 using location, number of reviews, amenities, etc.

## Requirements

The code was developed with Python 3.6. The key libraries used are:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn



## Usage

The notebooks contain the analysis walkthrough and can be run end-to-end. The scripts contain reusable functions.

To reproduce the analysis:

1. Download the [data](http://insideairbnb.com/get-the-data.html) and place in `data/` 
2. Run the notebooks in order

