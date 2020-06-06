# Climate-Analysis-and-Exploration
Climate Analysis and Exploration

This is a solo project to analyze the effects of latitude on climate. For the project, I created a Python script to visualize the weather from a random sample of 500+ cities across the world. I created scatterplots to visualize the relationship between latitude and aspects of climate including temperature, humidity, cloudiness and wind speed.
I then ran linear regressions on each relationship for both the Northern and Southern Hemispheres.
Finally I created a humidity heatmap for the cities and ploted hotels that were in areas of attractive climates using googlemaps.
### Tools/Packages Used:
* Pandas
* Time
* Matplotlib
* Scipy.stats

#### Scatterplots
The first set of plots show the relationships between latitude and climate in terms of temperature, humidity,cloudiness and wind speed. For example the following plot shows that there is a visible linear relationship between latitude and temperature, especially for the northern hemisphere.

![Temperature vs Latitude Plot](/output_data/Temp_Lat.png)
#### Linear Regression
The next set of plots show a linear regression of the first plots to quantify the relationships more exactly. For example, this plot shows a linear regression for the reationship between max temperature and latitude in the northern hemisphere

![Linear regression](https://github.com/mateoias/Climate-Analysis-and-Exploration/blob/master/output_data/linear%20regression%20of%20Max%20Temperature%20North%20vs%20Latitude.png)

#### Google API and Layers
The final question I looked at was to see which cities I might be interested in visiting based on weather conditions. The first layer is a humidity heat map from google.
![Humidity Heat Map](   )

The second Layer is a list of hotels that are in cities with suitable weather conditions for me. Some of the locations had no hotels within 5000 meters so they have been removed.
![Hotel Map ( )
