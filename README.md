# ForecastPulse ⛅🌡️

ForecastPulse is a weather app that provides real-time weather updates and forecasts for various locations using data from the OpenWeatherMap API.

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Bilal-dev07/ForecastPulse.git
```

```bash
cd forecastpulse
```

### 2. Install Dependencies

Install the required packages by running:

```bash
npm install
```

### 3. Add API Key

To access weather data, you’ll need an API key from OpenWeatherMap.

- Register at [OpenWeatherMap](https://openweathermap.org/) and obtain your API key.
- In the root directory, create a `.env` file and add your API key:

```bash
REACT_APP_API_KEY=your_openweathermap_api_key
```

### 4. Start the Application

Run the app in development mode:

```bash
npm start
```

The application will open in your default browser at [http://localhost:3000](http://localhost:3000).

## Features

- **Current Weather**: Get real-time weather details for your selected location.
- **Forecast**: View a 3-day weather forecast with easy-to-read icons and temperatures.

## Dependencies

- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Font Awesome** & **Weather Icons**: Icon libraries for weather visuals.

## Notes

Make sure to keep your API key secure and do not expose it in public repositories.

---

Enjoy using ForecastPulse!
