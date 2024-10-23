# Weather App - React

This is a simple Weather Application built with React that allows users to search for real-time weather information for any location. The app fetches weather data from the **OpenWeather API** and displays information like the current temperature (converted to Celsius), weather condition description (like "Clear" or "Cloudy"), feels like temperature, humidity, and wind speed.

## Features

- **Search for Any Location**: Users can type the name of any city and press "Enter" to retrieve the weather information.
- **Current Temperature in Celsius**: The temperature is fetched in Fahrenheit from the API and converted to Celsius using the appropriate formula.
- **Weather Condition**: The app displays the current weather description (e.g., Clear, Clouds, Rain) for the searched location.
- **Additional Weather Details**:
  - Feels like temperature (in Celsius).
  - Humidity percentage.
  - Wind speed (in miles per hour).
- **Responsive Design**: The UI is designed to be mobile-friendly and responsive across different screen sizes.
- **Modern React Practices**: The app uses up-to-date React best practices, such as the `onKeyDown` event handler and destructuring of event objects.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- **Node.js**: You’ll need Node.js (version 12 or higher) and npm (or Yarn) to run and build the project.
- **OpenWeather API Key**: You will need an API key from [OpenWeather](https://openweathermap.org/) to fetch weather data.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Dhairya-Anand/Weather-App-React.git
   cd weather-app-react
