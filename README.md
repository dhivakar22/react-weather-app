# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
# Weather App

Welcome to the Weather App! This React application allows you to search for the current weather conditions of any city using the OpenWeatherMap API.

## Features

- **Search Functionality**: Enter the name of a city in the input box and click the search icon to fetch weather data.
- **Current Weather Display**: View an image representing the current weather conditions.
- **Weather Details**: See the temperature, wind speed, and humidity for the searched city.

## Screenshots

![Weather App Screenshot]

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

## Components

- **SearchBar**: Contains the input box and search icon for entering the city name.
- **WeatherInfo**: Displays the weather image, temperature, wind speed, and humidity.
![Screenshot (623)](https://github.com/user-attachments/assets/ec22335a-97ae-46e2-be95-58fab32593ae)

## API Integration

The app uses the OpenWeatherMap API to fetch real-time weather data. The API request is made when the user enters a city name and clicks the search icon.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org) for providing the weather data.
- weather app screenshot 

---

Feel free to customize this README file acco![Screenshot (624)](https://github.com/user-attachments/assets/8aba4b15-51eb-45c0-bbff-19b02754f9df)
rding to your project specifics and preferences.
