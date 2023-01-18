# Evaluate Numeric Dataset UCI:Forest Fires 
[Forest Fires Data Set](https://archive.ics.uci.edu/ml/datasets/forest+fires)

Pauol Cortez and Anibal Morais aimed to predict the burned area of forest fires in the notheast region of Portugal, by using meterological and other data. 

Attribute information:
X - x-axis spatial coordinate within the Montesinho park map: 1 to 9
Y - y-axis spatial coordinate within the Montesinho park map: 2 to 9
month - month of the year: "jan" to "dec"
day - day of the week: "mon" to "sun"
FFMC - FFMC index from the FWI system: 18.7 to 96.20
DMC - DMC index from the FWI system: 1.1 to 291.3
DC - DC index from the FWI system: 7.9 to 860.6
ISI - ISI index from the FWI system: 0.0 to 56.10
temp - temperature in Celsius degrees: 2.2 to 33.30
RH - relative humidity in %: 15.0 to 100
wind - wind speed in km/h: 0.40 to 9.40
rain - outside rain in mm/m2 : 0.0 to 6.4
area - the burned area of the forest (in ha): 0.00 to 1090.84 (this output variable is very skewed towards 0.0, thus it may make sense to model with the logarithm transform).

This dataset is in thanks to Pauol Cortez and Anibal Morais. 
[Cortez and Morais, 2007] P. Cortez and A. Morais. A Data Mining Approach to Predict Forest Fires using Meteorological Data. In J. Neves, M. F. Santos and J. Machado Eds., New Trends in Artificial Intelligence, Proceedings of the 13th EPIA 2007 - Portuguese Conference on Artificial Intelligence, December, Guimarães, Portugal, pp. 512-523, 2007. APPIA, ISBN-13 978-989-95618-0-9.

# Evaluate Non-Numeric Dataset
[Airbnb Data for Analytics: Trentino Reviews](https://dataplatform.cloud.ibm.com/exchange/public/entry/view/9fc8543fabfc26f908cf0c592cf27867?context=cpdaas)

The dataset comprises of three main tables:
- listings - Detailed listings data showing 96 attributes for each of the listings. Some of the attributes used in the analysis are price(continuous), longitude (continuous), latitude (continuous), listing_type (categorical), is_superhost (categorical), neighbourhood (categorical), ratings (continuous) among others.
- reviews - Detailed reviews given by the guests with 6 attributes. Key attributes include date (datetime), listing_id (discrete), reviewer_id (discrete) and comment (textual).
- calendar - Provides details about booking for the next year by listing. Four attributes in total including listing_id (discrete), date(datetime), available (categorical) and price (continuous).

Some possible uses for data includes:
- analysis of star ratings of places
- location preferences
- analysis of tone and sentiment in reviews
- analysis of areas of dissastifaction 


# Evaluating Jupyter Notebooks
[Finding Optimal Locations for New Stores](https://dataplatform.cloud.ibm.com/exchange/public/entry/view/aceccfd155454fd9741852e12e9cce4e?context=cpdaas)
The notebook shows you how **Decision Optimization** can help to prescribe decisions for a complex constrained problem using Python to help determine the optimal location for a new store.

While visualizing locations of existing stores can provide great insights, it do not allow us to determin the locaiton of a new store easily. This is where an optimization model can be beneficial. 



