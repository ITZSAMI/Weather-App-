## Test it out: 
# Desktop Weather App (Python + PyQt5)

A lightweight desktop weather application built with Python and PyQt5.

The app allows users to enter any city name and instantly retrieve the current weather using the OpenWeatherMap API. It displays the temperature in Celsius, a short weather description, and an emoji that visually represents the weather condition.

## Features

- Search weather by city name
- Real-time data from OpenWeatherMap API
- Displays:
    - Temperature (°C)
    - Weather description
    - Condition-based emoji

- Handles common API and connection errors

## Technologies Used

- Python 3
- PyQt5
- requests
- OpenWeatherMap API

## How to Run
##1. Install dependencies

pip install PyQt5 requests

## 2. Add your API key

Create a free API key at https://openweathermap.org/

In the Python file, replace:

api_key = "YOUR_API_KEY"

Important: Do not upload your real API key to GitHub. If you already did, regenerate it from your OpenWeatherMap dashboard.

## 3. Run the application

python your_filename.py

(Replace your_filename.py with the actual name of your file.)

## How It Works

- The user enters a city name.
- The application sends a request to the OpenWeatherMap API.
- The JSON response is parsed.
- Temperature (in Kelvin) is converted to Celsius.
- The UI updates dynamically with:
  - Temperature
  - Description
  - A matching emoji based on the weather ID.

## Possible Improvements

- Add Celsius / Fahrenheit toggle
- Add 5-day forecast
- Use asynchronous requests to prevent UI blocking
- Package the app as an executable
