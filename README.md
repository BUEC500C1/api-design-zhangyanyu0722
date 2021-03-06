# Airport Weather Design Baesd on OpenWeather API

## Product Definition

### Project Mission
- For all USA Airports, Develop an API and module where we can get current conditions for the airport asked by the API and we can get current weather graphs for specific period.

### Target User(s)
- Travelers
- Airport Staff

### User Stories
- I, the traveler, want to know the location and weather conditions of the airport.
- I, the airport staff, want to know the visibility, wind, clouds and weather conditions.
- I, the traveler, want to know the wind and weather conditions of the destination.
- I, the traveler, want to know whether my flight will be delayed or not.

## How to use Open Weather API
### Download Files    
clone my repo and unzip it:   
```
git clone https://github.com/BUEC500C1/twitter-summarizer-zhangyanyu0722
```

### Register an API key of Open Weather     
Click this website https://home.openweathermap.org/users/sign_up for sign up, then you can get a free API ID
Open my openweathermap.py, use your API ID to replace mine:    
```
APIID = 'Your API ID'
```

For more information, visit the offical web : https://openweathermap.org/
<p align="middle">
  <img src= "https://github.com/BUEC500C1/twitter-summarizer-zhangyanyu0722/blob/master/picture/4.png" width= 500>
</p>

### Prepare Python Env and Pkg
Check Python Version : 
```
$ Python
Python 3.6.8 (v3.6.8:3c6b436a57, Dec 24 2018, 02:04:31) 
```
Install requests for current Python
```
$ pip install requests
```

### Run
Open a terminal, run
```
$ python openweathermaip.py
```
When you run the py program, terminal return as following: 
<p align="middle">
  <img src= "https://github.com/BUEC500C1/twitter-summarizer-zhangyanyu0722/blob/master/picture/1.png">
</p>

Choose "1" to input the city name
<p align="middle">
  <img src= "https://github.com/BUEC500C1/twitter-summarizer-zhangyanyu0722/blob/master/picture/2.png">
</p>

Input the city name, for example : Boston
<p align="middle">
  <img src= "https://github.com/BUEC500C1/twitter-summarizer-zhangyanyu0722/blob/master/picture/3.png">
</p>

Choose "2" to input the airport name
<p align="middle">
  <img src= "https://github.com/BUEC500C1/twitter-summarizer-zhangyanyu0722/blob/master/picture/44.png">
</p>

Input the airport name, for example : Total Rf heliport
<p align="middle">
  <img src= "https://github.com/BUEC500C1/twitter-summarizer-zhangyanyu0722/blob/master/picture/5.png">
</p>

## Compare OpenWeather API and National Weather API

- OpenWeather API need to sign up, then get a free ID, But National Weather API donot need to.
- In the OpenWeather API, the interface is
```
api.openweathermap.org/data/2.5/
```
- In the National Weather API, the interface is
```
https://api.weather.gov/
```
- The data from both API are all json.
- Generally, two API provide different kind of weather information, for example: Current weather API, Forecast, weather map...





