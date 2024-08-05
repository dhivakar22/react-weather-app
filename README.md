# Weather App

Welcome to the Weather App! This React application allows you to search for the current weather conditions of any city using the OpenWeatherMap API.

## Features

- **Search Functionality**: Enter the name of a city in the input box and click the search icon to fetch weather data.
- **Current Weather Display**: View an image representing the current weather conditions.
- **Weather Details**: See the temperature, wind speed, and humidity for the searched city.

## Screenshots

![Weather App Screenshot]

![Screenshot (624)](https://github.com/user-attachments/assets/25fd48ac-603f-4a8a-b7e2-01efbc02485c)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/weather-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd weather-app
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

1. Get your API key from [OpenWeatherMap](https://openweathermap.org/api).
2. Create a `.env` file in the root directory of the project and add your API key:
    ```
    REACT_APP_WEATHER_API_KEY=your_api_key_here
    ```
3. Start the development server:
    ```bash
    npm start
    ```
4. Open your browser and go to `http://localhost:3000`.

## Technologies Used

- React
- OpenWeatherMap API
- CSS for styling

## Components![Screenshot (624)](https://github.com/user-attachments/assets/20a681bf-08b1-4cfe-81c4-c9f8425dc21a)


- **SearchBar**: Contains the input box and search icon for entering the city name.
- **WeatherInfo**: Displays the weather image, temperature, wind speed, and humidity.

## API Integration

The app uses the OpenWeatherMap API to fetch real-time weather data. The API request is made when the user enters a city name and clicks the search icon.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org) for providing the weather data.

---

Feel free to customize this README file according to your project specifics and preferences.
