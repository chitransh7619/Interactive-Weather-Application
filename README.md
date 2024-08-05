# Weather Application

This is a React.js-based Weather Application designed to provide real-time weather information based on the user's location. The app utilizes the OpenWeatherMap API to fetch weather data and display it in a user-friendly interface. Key features and components include:

## Features
- **Real-Time Weather Updates:** Retrieves current weather conditions including temperature, humidity, visibility, and wind speed.
- **Location-Based Data:** Uses the user's geolocation to provide localized weather updates. Falls back to a default location (Delhi) if geolocation is not available.
- **Search Functionality:** Allows users to search for weather information in any city using a search bar.
- **Dynamic Weather Icons:** Displays animated weather icons that reflect current weather conditions.
- **Clock and Date Display:** Shows the current time and date for added context.

## Components
- **`App.js`:** The main component that renders the `CurrentLocation` component and footer information.
- **`currentLocation.js`:** Handles geolocation, fetches weather data from the OpenWeatherMap API, and displays current weather conditions and a clock.
- **`forecast.js`:** Provides a search functionality for different cities and displays weather data including temperature, humidity, visibility, and wind speed.

## Technologies Used
- **React.js:** JavaScript library for building user interfaces.
- **OpenWeatherMap API:** Service for retrieving weather data.
- **axios:** HTTP client for making API requests.
- **react-live-clock:** Component for displaying live time.
- **react-animated-weather:** Component for animated weather icons.

## Setup
1. Clone the repository: 
    ```bash
    git clone <repo-url>
    ```
2. Navigate to the project directory: 
    ```bash
    cd weather-app
    ```
3. Install dependencies: 
    ```bash
    npm install
    ```
4. Start the application: 
    ```bash
    npm start
    ```

## Notes
- Ensure that you have an active internet connection for fetching weather data.
- The application will prompt users to enable location services for accurate weather updates based on their current location.

## License
This project is licensed under the [MIT License](LICENSE).



![WebApp](https://github.com/user-attachments/assets/38af188e-1c0c-4b33-8f3d-f358f6dbbab8)


