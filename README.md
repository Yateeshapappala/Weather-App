
# 🌦️ Weather Application

## Overview
This Weather Application fetches real-time weather data using the OpenWeather API. It detects the user’s current location and shows the current weather and a 7-day forecast. Users can also search weather by city name. The app uses React, TypeScript, Redux Toolkit, React Router, MUI, and Styled Components for a scalable and elegant UI.

## Features
- Detect user location and show current weather using Geolocation API
- Search weather by city name
- 7-day weather forecast with temperature, humidity, wind speed, and icons
- Additional details like UV index, sunrise/sunset times
- Dynamic weather condition icons
- Dark/Light mode toggle using MUI ThemeProvider
- Responsive design for mobile, tablet, and desktop

## Tech Stack
- React + TypeScript  
- Redux Toolkit  
- React Router  
- Axios (for API calls)  
- Material-UI (MUI)  
- Styled Components  
- Custom Hooks for reusable logic  

## Setup Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
````

2. Navigate to the project folder:

   ```bash
   cd weather-app
   ```
3. Install dependencies:

   ```bash
   npm install
   ```
4. Create a `.env` file in the root directory and add your OpenWeather API key:

   ```
   REACT_APP_OPENWEATHER_API_KEY=your_api_key_here
   ```
5. Start the development server:

   ```bash
   npm start
   ```

The app will run on [http://localhost:3000](http://localhost:3000).

## Project Structure

* `/src/hooks` - Custom hooks including API calls
* `/src/features` - Redux slices and state logic
* `/src/pages` - App pages and routes
* `/src/routes` - Styled Components and theme files

## Future Improvements

* Save favorite locations
* Weather alerts/notifications
* Multi-language support

