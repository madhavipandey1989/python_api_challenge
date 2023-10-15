# python_api_challenge
 python_api_challenge

 WeatherPy.ipynb, downloads the city weather data from OpenWeather API, We plotted scatter plots for Latitude vs Max Temperature, Humidity, Cloudiness and Wind Speed, calculated liner regression for each of them, and identified if the Latitude impactes Temperature, Humidity, Cloudiness or wind speed. Temperature does decrease when Latitude increases. 

Output of citi data stored in citis.csv
Graph outputs are stored in Latitude_cloudiness.png, Latitude_Humidity.png, Latitude_Temp.png, Latitude_WindSpeed.png. 

VacationPy.ipynb loads the data from citis.csv, and identifies each city on world map. Reduced the dataset to only use the citis which are <27 decree Celcius and more than 21 degree celcius in temperature, no cloudiness, and wind speed of 4.5. We filtered data to create another dataframe for hotels. Used Geoapi to get hotel names from  10000 meters of the geo location of city, and potlled the new dataset on maps. This will help us to plan our next vacation. 


