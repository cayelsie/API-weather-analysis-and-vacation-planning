The first goal of this project was to obtain the current weather from 500+ cities across the globe and plot some common weather measurements vs city latitude to examine any possible correlations. This allows an analysis of cities' weather in conjunction with distance from the equator. This data was gathered using a Python library called Citypy (https://pypi.org/project/citipy/) and the OpenWeatherMap API (https://openweathermap.org/api). Plots were created using Pandas in Jupyter notebook with Matplotlib. The files associated with this part of the project are located in the WeatherPy folder. To run the notebook (WeatherPy_main.ipynb) and make the API calls, a working OpenWeatherMap API key will need to be inserted into the api_keys.py file.
The second goal of the project was to filter the chosen cities from the weather analysis by my ideal weather conditions for a vacation spot (max temperature between 70 and 80 degrees, humidity less than 65%, cloudiness less than 10% and wind speed less than 10 mph), find hotels within 5000 meters of each city and then create a humidity heatmap of the hotel locations. The hotels were found using Google Places API. The heatmap was created using Pandas in Jupyter notebook using Jupyter gmaps. The files associated with this part of the project are located within the VacationPy folder. To run the notebook (VacationPy_main.ipynb) and make the API calls, a working OpenWeatherMap API key and a working Google API key will need to be inserted into the api_keys.py file.  