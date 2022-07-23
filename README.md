# World_Weather_Analysis
### Project Overview:
    - The purpose of this project was to generate random potential destination locations for travel customers looking 
    to find a vacation spot with certain weather criteria. First, we generated random longitude and latitude pairs. Then 
    we used a weather API, openweathermap.org/api, to search for weather criteria(maximum temperature, minimum temperature, 
    humidity, cloudiness, and wind speed) based on the cities nearest the random latitude and longitude pairs we generated. 
    From there we generated an input for travel customers to specify what kind of max and min temperatures they prefer for 
    their vacation destination, which generated a list of preferred cities that the travel customers could pick from based 
    on their temperature preferences. From here we used Google APIs to find hotels near the preferred cities and generated 
    maps with markers of the potential hotel locations. We made the markers pop-up markers which showed details such as city 
    name, country code, hotel name, maximum temperature, and current weather description for the specific marker.   
