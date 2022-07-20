# Avocado Price Prediction

*Project highlighting the use of time-series methods for price forecasting and prediction* - 

**Problem Statement:** The Hass Avocado Board, an American-based trade organization helps in the production of a variety of Avocados which are
sold in the US. They have been having good success for the past several years and
want to expand. For this, they want to build and assess a plausible model to predict
the average price of Hass avocado to consider the expansion of different types of
Avocado farms that are available for growing in other regions.

**Aim**: Forecast the prices of Avocado in the US

**Data**: The data comes directly from retailers’ cash registers based on the actual retail sales
of Hass avocados.

* Data represents weekly retail scan data for National retail volume (units) and
price from Apr 2015 to Mar 2018.
* The Average Price (of avocados) in the table reflects a per unit (per avocado)
cost, even when multiple units (avocados) are sold in bags.
* The Product Lookup codes (PLU’s) in the table are only for Hass avocados.
Other varieties of avocados (e.g. greenskins) are not included in this table.
Some relevant columns in the dataset:
1. Date - date of the observation
2. AveragePrice - average price of a single avocado
3. Type - conventional / organic
4. Region - region of the observation
5. Total Volume - Total number of avocados sold
6. 4046 - Total number of avocados with PLU 4046 sold
7. 4225 - Total number of avocados with PLU 4225 sold
8. 4770 - Total number of avocados with PLU 4770 sold
9. Total Bags – Total bags sold
10.Small/Large/XLarge Bags – Total bags sold by size
As mentioned above there are two types of avocados in the dataset as well as several different regions represented. All sorts of analysis for different areas of the United States, specific cities, or just the overall United States on either type of avocado is possible. The analysis will be focused on the complete dataset.

* Kaggle link to original dataset: https://www.kaggle.com/datasets/neuromusic/avocado-prices
