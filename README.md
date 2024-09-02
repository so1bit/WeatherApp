# Weather App

## Overview
This Weather App is a simple, intuitive application that allows users to check the current weather and a 24-hour forecast for any city in the world. It fetches weather data using the OpenWeatherMap API and displays it in a user-friendly interface.

## Features
- **Current Weather**: Displays the current temperature, weather condition, and an icon representing the weather.
- **24-Hour Forecast**: Provides a forecast for the next 24 hours in 3-hour intervals, including temperature and weather icons.
- **Responsive Design**: The app is designed to be responsive and works well on various screen sizes.

## Technologies Used
- **HTML/CSS**: For creating the structure and styling of the app.
- **JavaScript**: For fetching data from the API and dynamically updating the UI.
- **OpenWeatherMap API**: To fetch the current weather and forecast data.

## Setup and Usage
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. **Open `index.html` in your web browser:**
    Simply double-click the `index.html` file or drag it into a browser window.

3. **Enter a city name:**
    Type the name of a city into the input box and click the "Search" button. The app will display the current weather and a 24-hour forecast for the entered city.

## API Key Configuration
The app uses the OpenWeatherMap API, and you'll need an API key to make requests. The API key is already included in the `index.html` file. If you want to use your own API key:
1. Sign up for an API key at [OpenWeatherMap](https://openweathermap.org/api).
2. Replace the `apiKey` variable in the `getWeather()` function in the `index.html` file with your API key.

```javascript
const apiKey = 'your-own-api-key';
