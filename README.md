# Weather App

## Description
The **Weather App** is a user-friendly web application that provides real-time weather information for cities around the world. The app fetches accurate weather data using the OpenWeatherMap API and displays essential details such as temperature, weather conditions, and a visual icon representation. With its clean design and responsive layout, the app ensures a seamless user experience on both desktop and mobile devices.

## Features
- **Search Functionality**: Allows users to search for the current weather by entering the city name.
- **Real-Time Weather Data**: Displays temperature, weather conditions, and an icon for easy visualization.
- **Responsive Design**: Optimized for use on various devices, including desktops, tablets, and mobile phones.
- **Dynamic Icons**: Weather conditions are represented by icons for better clarity.
- **(Optional)**: Hourly weather forecast displayed in a scrollable format.

## Technologies Used
- **HTML5**: Markup for the app structure.
- **CSS3**: Styling and responsive design.
- **JavaScript**: Dynamic functionality, API integration, and event handling.
- **OpenWeatherMap API**: Fetches real-time weather data.

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Open the `index.html` file in your preferred web browser:
   ```bash
   open index.html
   ```

## Usage
1. Open the Weather App in your web browser.
2. Enter the name of the city you want to check the weather for.
3. Click the **Search** button to fetch the weather data.
4. View the current temperature, weather condition, and icon.

## API Key Setup
1. Sign up for an API key from [OpenWeatherMap](https://openweathermap.org/api).
2. Add your API key in the `scripter.js` file:
   ```javascript
   const apiKey = "YOUR_API_KEY_HERE";
   ```

## File Structure
```
weather-app/
├── index.html       # Main HTML file
├── style.css        # Stylesheet for the app
├── scripter.js      # JavaScript for functionality
└── README.md        # Project documentation
```

## Future Enhancements
- Add a 7-day weather forecast feature.
- Implement geolocation to fetch the user's current weather automatically.
- Display additional weather details like humidity, wind speed, and sunrise/sunset times.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [OpenWeatherMap](https://openweathermap.org/) for providing the weather API.
- Inspiration from beginner-friendly weather app tutorials.

---

Feel free to fork and contribute to this project!
