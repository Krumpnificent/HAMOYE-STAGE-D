#  Exploratory Data Analysis of Africa Agriculture (2004 - 2013)

Agriculture is Africa's most important economic activity, providing employment for about two-thirds of its working population. This project aims to provide insights into Africa's agricultural activities from 2004 to 2013 through exploratory data analysis.

## Project Overview

The project follows a systematic approach of cleaning, describing, analyzing, and visualizing the data on Africa's food production and supply. The main objectives are:

1. Clean and preprocess the data.
2. Explore the data to identify trends and patterns.
3. Answer questions about food production and supply in Africa.
4. Visualize the data to gain a better understanding.

## Technologies Used

The project utilizes the following libraries and modules:

- Python
- pandas
- matplotlib
- seaborn
- numpy
- datetime
- geopandas
- plotly
- dataframe_image

## Data Import

The project imports two datasets: 

- `Africa Food Supply (2004 - 2013).csv` contains data on food supply in Africa.
- `Africa Food Production (2004 - 2013).csv` contains data on food production in Africa.
- `population.csv` contains data on population of countries
- `countries.geojson` contains data on geographical locations of countries

## Exploratory Data Analysis

The exploratory data analysis process involves the following steps:

1. Data Cleaning:
   - Convert column names to lowercase.
   - Convert the 'year' column to datetime format.
   - Extract the year from the 'year' column.
   - Rename columns for clarity.

2. Data Transformation:
   - Group the food production data by country and year, and calculate the total production for each year.
   - Merge the data with a geopandas dataset to create visualizations.
   - Convert population data from wide to long format
   - Merge food supply data with population data for unit conversions

3. Data Exploration:
   - Identify the number of unique countries, years, and food products.
   - Determine the top 5 most produced food items in Africa.
   - Identify the top 5 food-producing countries in Africa.
   - Analyze the top 5 food items produced in Nigeria.

4. Data Visualization:
   - Create choropleth maps to visualize food production by country and food supply by country from 2004 to 2013.
   - Identify the outliers in food supply data.
   - Compare food production and supply to analyze food deficit and oversupply.

## Results

- The top 5 food-producing countries in Africa from 2004 to 2013 are Nigeria, Egypt, South Africa, Ethiopia, and Tanzania.
- The top 5 food items produced in Nigeria are Cassava, Maize, Yams, Rice (Milled Equivalent), and Sorghum.
- The choropleth map of food production by country shows that Nigeria, Egypt, and South Africa consistently remained the top food producers.
- The choropleth map of food supply by country shows that Egypt, Morocco, and Tunisia had the highest food supply per capita.
- Outliers in food supply are identified, and Egypt is found to be the only outlier in the dataset.

## Conclusion

The exploratory data analysis provides valuable insights into Africa's agricultural activities from 2004 to 2013. The analysis highlights the top food-producing countries, the most produced items, and the disparities in food supply across the continent. By visualizing the data, patterns and trends in food production and supply are easily identifiable.

This project serves as a foundation for further analysis and research on Africa's agriculture and can be extended to explore additional aspects such as crop yields, agricultural practices, and their impact on food security.
