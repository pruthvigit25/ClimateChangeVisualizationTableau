# Indian Summer Climate Change Visualization

## Introduction
I have chosen a dataset of "Indian Summer – Over the years" to visualize the effect of climate change over the years. The visualization aims to predict the weather conditions of the top cities while comparing the values of the past ten years' data. An interactive dashboard has been created to aid the visualization and deal with the complexity of the large dataset.

## Dataset
The dataset was sourced from Kaggle and consists of 13,651 items and 20 attributes. It covers three months in the summer of ten years (2012-2021). The data has been pre-processed to shape the visualization. The dataset includes a mixture of data types such as strings, whole numbers, decimal numbers, and dates. Additionally, the respective state names for the corresponding cities were added to visualize the geographical locations. The visualization incorporates quantitative and categorical attributes, including tables, geometry, sets, lists, and clusters.

### Attributes
Attributes of RAW data: Date, minimum, maximum and average temperature, minimum, maximum and average feels-like temperature, dew, humidity, windspeed, wind direction, sea level pressure, cloud cover, visibility, sunrise and sunset time, moon phase, and weather conditions.

Attributes of pre-processed data: Date, minimum, maximum and average temperature, humidity, windspeed, wind direction, cloud cover, visibility, sunrise and sunset time, moon phase, and weather conditions.

No items were removed or filtered from the dataset.

### Techniques for Pre-processing
- Metadata and Statistical Analysis: Mean values were considered for minimum and maximum temperature, windspeed, wind direction, cloud cover, moon phase, and visibility.
- Data Cleansing: Five attributes were removed due to the complexity of visualizing the large dataset.
- Normalization: Data was scaled to facilitate comparison across different cities.

## Visualization Idioms and Tasks
The visualization utilizes five different idioms to represent the dataset:

1. **Choropleth Map:** This idiom uses a geographic choropleth map to represent different Indian cities, labeling the weather conditions of each city from 2012 to 2021. Color and position serve as encoding channels. The interactive dashboard allows filtering of individual or multiple cities to explore weather conditions. The task is to identify the city with the most variation in climate over the years and determine the best city to visit during Indian summers based on conditions.

2. **Line Chart:** The average maximum and minimum temperatures of ten years are represented using a line chart idiom. Different colors represent each city, enabling comparison of temperature variations over the years. From the line chart, it can be concluded that Bangalore has the most favorable temperature during summers, while Ahmedabad experiences the highest temperatures. However, temperature has been declining in Ahmedabad over the past four years.

3. **Packed Bubbles:** This idiom presents the sunrise and sunset timings of each city from 2012 to 2021, along with the humidity value. Each color represents a different year, and cities can be selected from a drop-down menu to check and compare values. Bubble size represents humidity, with larger bubbles indicating higher humidity. This visualization helps analyze how humidity has changed over the years for different cities and compare sunrise and sunset times.

4. **Dual Graph:** Average wind speed and direction over the years are presented using a dual chart idiom. The graph can be filtered by cities to find the average wind speed and direction for each city. The idiom uses different shapes to differentiate between wind speed and direction. This visualization allows for comparison of changes over the years across different cities, providing insights into wind patterns and enabling predictions for future wind conditions.

5. **Vertical Bar Graph:** This idiom represents the average cloud coverage, visibility, and moon phase values for top Indian cities using a vertical bar graph. The data is arranged in ascending order, with the year with the minimum cloud coverage value displayed first, followed by the ascending order of years. The brightness of the graph represents the moon phase value for each year. This visualization allows for easy comparison of values across different years for each city. For example, in Mumbai, 2021 had the highest cloud coverage value compared to the last ten years, while 2019 had the lowest cloud coverage value. The brightness of the graph indicates the least moon phase value in 2014. This data helps identify the years with the highest/lowest values for each city.

The visualization combines these five idioms to create a "Weather Conditions of Top Indian Cities" dashboard. Users can filter city names and years to observe changes in the weather conditions. Multiple cities can be selected for comparison, such as comparing the temperature graph of different cities. Geographical maps use different colors to represent each state. All plots are color-coordinated to attract the audience's attention.

## Novelty
This dashboard presents the dataset using a combination of multiple idioms and encoding channels in a novel way. It effectively communicates the idea behind the visualization. Different colors are used to distinguish and compare city values. The visualization incorporates various idioms and encoding channels to represent the dataset, as explained earlier. The complexity of the dataset required filtering of some attributes to improve visualization. While the visualization would benefit from animation, displaying one idiom at a time, it effectively visualizes the dataset within the given time constraints. Although the dataset only includes data from top Indian cities, incorporating values from all Indian states would enhance the visualization.

## Critical Analysis
The visualization aims to be understandable even to audiences with limited technical knowledge. Different idioms and encoding channels are employed to aid the visualization. However, the visualization would benefit from animating the idioms to focus on one at a time, as multiple idioms can cause visual clutter. The dataset includes data from top Indian cities only, limiting the broader representation of Indian states. Overall, the dataset is visualized in the best possible way within the given time constraints.

## Tools Used
Tableau 


