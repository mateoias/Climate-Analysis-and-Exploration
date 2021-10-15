# Climate-Analysis-and-Exploration
Climate Analysis and Exploration: Note that the code will not run as I removed the google API key

![test](Climate-Analysis-and-Exploration/Screen Shot 2021-04-06 at 6.59.13 PM.png)


This is a solo project to analyze the effects of latitude on climate. For the project, I created a Python script to import the weather from a random sample of 500+ cities across the world. I created scatterplots to visualize the relationship between latitude and aspects of climate, including temperature, humidity, cloudiness and wind speed.
I then ran linear regressions on each relationship for both the Northern and Southern Hemispheres.
Finally I created a humidity heatmap for the cities and plotted hotels that were in areas of attractive climates using google maps.
### Tools/Packages Used:
* Pandas
* Jupyter Notebook
* Time
* Google Maps API
* Matplotlib
* Scipy.stats

#### Questions that I addressed

##### Is there a clear relationship between latitude and climate?
I first created a set of scatterplots showing the relationships between latitude and climate in terms of temperature, humidity, cloudiness and wind speed. For example the following plot shows that there is a visible linear relationship between latitude and temperature, especially for the northern hemisphere.

![Temperature vs Latitude Plot](/output_data/Temp_Lat.png)
#### Linear Regression
Next I created a set of plots showing a linear regression of the first plots to quantify the relationships more exactly. For example, this plot shows a linear regression for the relationship between max temperature and latitude in the northern hemisphere. The first two plots show the relationship between temperature and latitude. There is an evident visual correlation and the r**2 value of .62 gives a high confidence to our intuition that temperature
is strongly affected by latitude.


![Linear regression](https://github.com/mateoias/Climate-Analysis-and-Exploration/blob/master/output_data/linear%20regression%20of%20Max%20Temperature%20North%20vs%20Latitude.png)

##### How can we map hotels that are located in a climate suitable for a vacation?

I prefer a dry climate and I hate rain so the final question I looked at was to see which cities I might be interested in visiting based on weather conditions. The results are displayed as layered google maps; the first layer is a heat map showing the humidity for all of the cities that I investigated.
![Humidity Heat Map](https://github.com/mateoias/Bootcamp-Work/blob/master/07_API/output_data/humidity_map.png  )

The second layer of the map shows hotels that are in cities with suitable weather conditions for my vacation. Some of the cities with a suitable climate had no hotels within 5000 meters so they have been removed.
![Hotel Map](https://github.com/mateoias/Bootcamp-Work/blob/master/07_API/output_data/Top_Hotels_Map.png )
