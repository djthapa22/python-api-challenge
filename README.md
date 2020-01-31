# Python API Challenge

Data analysis of world weather data to better understand and explain what the weather is like close to the equator. Used Python, Matplotlib, Citipy, the OpenWeatherMapAPI, the Google Places API, and other technologies to help create a representative model of weather across world cities.

* [Background](#background)
* [Observations and Insights](#insights)
* [Jupyter Notebook](#nb)
* [Images](#images)
* [Technologies Used](#technologies)

## <a name="background"></a>Background



## <a name="insights"></a>Observations and Insights

Observations or inferences that can be made from the data.

* There is a strong, negative correlation between a city's latitude and maximum temperature in the northern hemisphere. That is, as you go farther away from the equator (latitude increases), a city's maximum temperature will generally be lower than cities closer to the equator in the northern hemisphere.
* There is a very weak, positive correlation between cloudiness and a city's latitude for both the northern and southern hemispheres. This is represented in the scatter plots in this notebook for those two factors as the data points being scattered across the graph. As a result, we can conclude that a city's latitude has little to no influence on how cloudy a city is.
* There is a very weak, positive correlation for the northern hemisphere between a city's latitude and wind speed (mph), and there is a very weak, negative correlation for the southern hemisphere for those same two factors. As a result, latitude has a small influence on wind speed but not very much. However, it is important to note that the correlation between these two factors for the southern hemisphere is stronger than the correlation between these two factors for the northern hemisphere.

## <a name="nb"></a>Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. There are two notebook files for part 1 (WeatherPy) and part 2 (VacationPy) of this project.

* [WeatherPy](./WeatherPy/WeatherPy.ipynb)
* [VacationPy](./VacationPy/VacationPy.ipynb)

## <a name="nb"></a>Images

* Static images of the different visualizations can be found [here](./WeatherPy/Images).

## <a name="technologies"></a>Technologies Used

* Python
* Pandas library
* Jupyter Notebook
* Matplotlib library
* Citipy
* OpenWeatherMap API
* Google Places API
* jupyter-gmaps
