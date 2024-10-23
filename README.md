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

2. **Install Dependencies: After cloning the project, install the required dependencies by running**:
    ```bash
    npm install

3. **Run the App: Once the setup is complete, you can run the app locally**:
    ```bash
    npm start

**This will start the development server, and you can view the app by visiting http://localhost:3000 in your browser.**

## Key Components

- **Search Bar: Allows users to input a city name and press "Enter" to search for weather information.**
- **Weather Display: Shows the current temperature, weather description, and additional details like "Feels Like" temperature, humidity, and wind speed.**
- **Temperature Conversion: The app fetches temperature data in Fahrenheit and converts it to Celsius using a custom function.**

## Technology Stack

- **React: JavaScript library for building the user interface.**
- **Axios: Used for making HTTP requests to the OpenWeather API.**
- **CSS: Styling is done using modern, responsive CSS.**