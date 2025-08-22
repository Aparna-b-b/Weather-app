# WeatherApp

A simple and responsive React-based weather application that fetches and displays real-time weather information for any city using the OpenWeatherMap API.

## Features

- Search for any city worldwide and view its current weather conditions.
- Displays temperature, humidity, wind speed, and weather icon based on live data.
- Intuitive and visually appealing user interface with responsive design.
- Dynamic weather icons that change according to weather conditions.
- Built with React functional components and hooks.

- ## Screenshots
 ![App Screenshot](./screenshots.png)


## Technologies Used

- React.js (Functional Components, Hooks)
- OpenWeatherMap API
- CSS Flexbox & Gradient Styling
- Fetch API for asynchronous requests

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- An API key from [OpenWeatherMap](https://openweathermap.org/api)

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/weather-app.git

2.Navigate into the project directory

   cd weather-app


3.Install dependencies

  npm install


4.Create a .env file in the root directory and add your OpenWeatherMap API key

  REACT_APP_WEATHER_API_KEY=your_api_key_here


5.Start the development server

  npm start


The app should now be running at http://localhost:3000
.

### Usage

Enter the name of a city in the search bar.

Click the search icon or press enter.

View the current weather details for the city, including temperature, humidity, wind speed, and a matching weather icon.

### Folder Structure

```weather-app/
│
├── public/
├── src/
│   ├── Assets/          # Weather and UI icons
│   ├── Components/
│   │   └── WeatherApp/  # Main weather app component and styles
│   ├── App.js
│   ├── index.js
│   ├── App.css
│   └── WeatherApp.css
├── .env                 # Environment variables (API key)
├── package.json
└── README.md```


### API Reference

   Weather data is fetched from the OpenWeatherMap Current Weather Data API
.

### Contributing

   Contributions, issues, and feature requests are welcome! Feel free to check the issues page
.

License

This project is licensed under the MIT License. See the LICENSE
 file for details.

Contact

Created by Aparna B B
 – feel free to contact me!
