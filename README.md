# WeatherAPI
The objective of this project was to analyze the effect of latitude on the following weather variables: temperature, humidity, cloudiness, and wind speed. To get the 500 randomly selected cities I used a CSV file from the Citypy Python library Github repository and the sample method. Once I had my 500 randomly selected zip codes, I pulled weather data for those locations from the Open Weather API. I then used this data to generate scatter plots using Matplotlib to analyze the correlation between latitude and the afore mentioned weather variables. 

These are the insights I found:
1. The highest temperature by latitude does form a predictable curve, however, it is not centered around the equator. Instead the highest point in the curve of the graph is centered around 20 degrees latitude. This is because it is summer in the Northern hemisphere so the highest temperatures are slightly north of the equator. 

2. There does not seem to be a relationship between humidity and latitude. 

3. There also does not seem to be a relationship between cloudiness and latitude or wind speed and latitude. 
