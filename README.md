<h1 align="center">Welcome to weather-app-details 👋</h1>
<p>
  <a href="https://www.npmjs.com/package/weather-app-details" target="_blank">
    <img alt="Version" src="https://img.shields.io/npm/v/weather-app-details.svg">
  </a>
  <a href="#" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/badge/License-ISC-yellow.svg" />
  </a>
</p>

> Contains data for Weather Application

## Install

```sh
npm install weather-app-details
```

## Usage

```javascript
// This package exports three functions, i.e) allTimeZones(),  timeForOneCity(),  nextNhoursWeather()
const {
  allTimeZones,
  timeForOneCity,
  nextNhoursWeather,
} = require("weather-app-details");

// allTimeZonesData contains the allcitiesdata like CityName, DateAndTime, TimeZone, Temperature, Humidity, Precipitation values
let allTimeZonesData = allTimeZones();

// timeForACity consists of DateAndTime along with city Name for provided city name
let timeForACity = timeForOneCity(cityName);

// nextNHoursWeatherData consists of next n requested hours temperature
let nextNHoursWeatherData = nextNhoursWeather(
  dateAndTime,
  hours,
  allTimeZonesData
);
```

## Author

👤 **Vijai Sivakumar**

- Github: [@ks-vijai](https://github.com/ks-vijai)

## Show your support

Give a ⭐️ if this project helped you!

---
