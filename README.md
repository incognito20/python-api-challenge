# python-api-challenge

# WeatherPy pulls a random list of cities ~500 from across the world. This list is used to query the Open Weather API to gather weather details and coordinates from each city. Relationships between temperature, humidity, cloudiness, and wind speed are plotted and linear regression is used to identify if there are relationships between the variables based on northern and southern hemisphere.

#VacationPy utilizes the output from WeatherPy and maps all cities with the size of the city point reflecting its humidity value. The list of cities is narrowed down to my ideal weather conditions and a list of nearest hotels is gathered, if available. Those hotel names and the country of the city is included in the information as you hover over the city on the map.