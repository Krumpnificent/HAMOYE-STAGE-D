# Pattern Recognition
The goal of this analysis was to find trends and patterns in food production and supply by African countries from 2004 to 2013.

## Intoduction
Agriculture is Africa’s most important economic activity. Africa has a large population working in Agriculture as it provides employment for about two-thirds of its working population. Data on Africa’s food production and supply hold some very interesting insights about its agricultural activities which are not easily explained by mere words. This project provides insights into Africa’s agricultural activities from 2004 and 2013. I made sure to comment my codes efficiently given i used a lot of variables as i wrangled the data.

## About the datasets
The dataset consist of a population table, a geojson file for country locations, a food prodution and a food supply table. 

The unit food produced was kiloton while the unit of food supply was kcal/person/day (this was converted to kiloton in my analysis)

## About the data cleaning
Something worthy of mentioning is the change of country names in certain tables. This was done to have same country names in tables to avoid loss of data when joining. Some countries appeared to have varying identities in different tables; there was need for symmetry.

## How to use visuals
**food production and food supply visuals**; can be operated in similar ways by simply clicking the 'play' button attached to each of them or using the sliders below them to view food production/supply results for each year.

**Outlier in food supply visual**; can be changed by altering the year argument within the plot() funtion.
