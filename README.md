# JT-weather-dash
This is a live real-time weather dashboard, utilizing live weather data from openweathermap.org

## Description
The Weather Dashboard is a web application that provides users with current weather conditions, forecasts, and other weather-related data for any city around the world. This project uses data from [OpenWeatherMap.org](https://openweathermap.org/) and features a simple, user-friendly interface designed for quick and easy access to live, real-time weather information.

## Features
- **Search Functionality**: Look up the weather for any city.
- **Current Weather Conditions**: Displays temperature, humidity, wind speed, and weather description.
- **5-Day Forecast**: Provides daily weather forecasts for the next five days.
- **Dynamic Icons**: Shows weather-specific icons for an intuitive user experience.

## Technologies Used
- **Front-End**: Vite, React, HTML, CSS, JavaScript
- **Back-End**: Node.js, Express
- **API**: OpenWeatherMap API
- **Hosting**: Render

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-dashboard
   ```

3. Install dependencies for both the client and server:
   ```bash
   cd client && npm install
   cd ../server && npm install
   ```

4. Start the development servers:
   - **Client**: Run the following command in the `client` folder:
     ```bash
     npm run dev
     ```
   - **Server**: Run the following command in the `server` folder:
     ```bash
     npm start
     ```

5. Open your browser and navigate to the provided URL to access the app.

## Usage
1. Enter a city name into the search bar.
2. View the current weather conditions and the 5-day forecast.
3. Explore additional weather data such as humidity and wind speed.

## Deployment
The application is deployed using [Render](https://render.com/):
- Front-End: [Deployed Front-End Link](#)
- Back-End: [Deployed Back-End Link](#)

## Environment Variables
To run this project locally, set up the following environment variables:

- **Client (`client/.env`)**:
  ```env
  VITE_API_URL=http://localhost:3000
  ```

- **Server (`server/.env`)**:
  ```env
  PORT=3000
  OPENWEATHER_API_KEY=<your-api-key>
  ```

Replace `<your-api-key>` with your OpenWeatherMap API key.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data.
- [Render](https://render.com/) for hosting and deployment.


