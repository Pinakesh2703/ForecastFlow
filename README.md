# ForecastFlow

![image](https://github.com/user-attachments/assets/210162cb-157e-4a1a-b60a-7d23373fe276)

# Weather App

A simple weather application that provides current weather details and a 5-day forecast for any city. The app integrates with the OpenWeatherMap API to fetch weather data and uses Leaflet.js to display the city location on a map.

## Features

- Display current weather information including temperature, humidity, wind speed, and pressure.
- Show a 5-day weather forecast.
- Locate and display the city on a map using Leaflet.js.



## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/ForecastFlow.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Forecastflow
   ```
3. Open `index.html` in your favorite browser.

## Usage

1. Enter a city name in the input field.
2. Click the "Search" button to fetch and display the weather information.
3. The map will update to show the location of the searched city.

## Technologies Used

- HTML
- CSS
- JavaScript
- [OpenWeatherMap API](https://openweathermap.org/api)
- [Leaflet.js](https://leafletjs.com/)

## Code Overview

### HTML

The HTML structure includes:
- A search form to input the city name.
- Containers to display weather information and a map.

### CSS

The CSS provides:
- Dark-themed styling for the entire application.
- Responsive design for different screen sizes.

### JavaScript

The JavaScript code:
- Fetches current weather data and a 5-day forecast from the OpenWeatherMap API.
- Displays the weather information.
- Initializes and updates the map using Leaflet.js.

### API Key

Replace `'xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'` with your own OpenWeatherMap API key in the JavaScript section of `index.html`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any bugs or feature requests.

