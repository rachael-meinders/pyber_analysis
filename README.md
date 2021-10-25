# PyBer Analysis

## Project Overview
A ride-sharing company, PyBer, has tasked me with an exploratory analysis to collect and visualize data about different types of cities, and the rides, drivers, and fares for each.

### Purpose
1. Inspect and clean all data sources.
2. Construct summaries for each city type.
3. Caluclate the following variables for each city type:
  - number of rides
  - average fare
  - average number of drivers.
5. Create bubble charts to visualizethe above variables for each individual city type.
6. Compile these charts into a single bubble chart.
7. Identify any outliers using box-and-whisker charts.
8. Visualize each city type's proportion of the above variables.

### Results
![Fig1](https://user-images.githubusercontent.com/90879979/138760237-57a4ef92-af8a-458a-9474-d82919925bcc.png)

![box_and_whiskers](https://user-images.githubusercontent.com/90879979/138760211-80d11da6-8539-44f6-8a18-5dd877fc5b4b.png)

![pie_charts](https://user-images.githubusercontent.com/90879979/138760218-eba95160-8d20-4f4e-a05b-3fcb8382043b.png)

### Resources
- Data Sources: Resources/city_data.csv
                         /ride_data.csv
                         /PyBer_ride_data.csb
- Software: Python 3.6.1, Jupyter Notebook

## Challenge Overview
The challenge is meant to summarize, compare, and visualize the total PyBer fares by city type.

### Challenge Purpose
1. Create a dataframe that summarizes the total fare for each city type.
2. Visualize the total weekly fares for each type of city.

## Challenge Results
![Fig8_challenge](https://user-images.githubusercontent.com/90879979/138760268-db4d5ce0-0b58-4995-84cc-211ee89240f6.png)

## Summary
- One outlier was identified: an urban city in the ride count variable. Further analysis excluding this data point may prove useful in small-scope situations, such as those that only focus on rural cities. However, this data point likely does not alter results significantly for larger-scope situations.
- Rural cities are seemingly under-represented and/or under-served by PyBer. Expansion in these market will likely prove fruitful, provided a steady demand.
- Total fares hit a peak for each city type in late-February. 
- Total fares are surprisingly low for the beginning of the year considering New Year's Eve and New Year's Day typically provide an increased demand. PyBer may be able to increase business in this timeframe with increased advertising or special deals that encourage intoxicated people to use PyBer. 
