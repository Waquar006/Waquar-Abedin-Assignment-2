# weather-advisor_waquar-abedin
A Python app that provides weather forecasts and answers weather questions. Following are the core functionalities included: 

**get_weather_data function and error handling**

Fetches current weather and a forecast weather for up-to 5 days at a specified location. 

 **Description**
  - Fetches current temperature, real feel temperature, weather description,      humidity, and wind speed.
  - Fetches weather forecast data for select number of days (1–5).
  - Returns data in a formatted manner.
  - Handles invalid inputs, network issues, and API errors.

**Weather NLP Parser & Fetcher**

This allows users to ask conversational questions related to weather and get structured answers. It combines NLP Parsing with real time weather data and context aware conversation processing. 

 **Description:**
 - Adds functions to extract locations and attributes, supports negation detection, and parses time expressions.
 - Maintains conversation awareness and responds based on context.
 - Provides a confidence rating for each element or attribute.
 - Handles invalid input or netowork errors. 
