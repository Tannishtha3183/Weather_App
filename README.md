# India Weather Explorer

A browser-based weather intelligence app focused on Indian cities.

This project provides a single-page interface to explore real-time weather, forecasts, air quality, alerts, and comparative analytics for major cities across India. It is designed for practical use: checking conditions, comparing cities, and understanding weather trends visually.

---

## Overview

India Weather Explorer combines live API data with a built-in city dataset to deliver weather information without requiring a backend server.

The project emphasizes:

- Instant weather lookup
- Visual comparison
- City-based filtering
- Forecast analysis
- Air quality insights
- Alerts based on conditions
- Interactive charts

Everything runs in the browser using HTML, CSS, and JavaScript.

---

## Features

### Current Weather

View real-time conditions for supported Indian cities:

- Temperature
- Feels like
- Humidity
- Pressure
- Wind speed
- Weather description
- Condition icon

Powered by OpenWeather API. :contentReference[oaicite:2]{index=2}

---

## 5-Day Forecast

Forecast module provides:

- Daily breakdown
- Temperature overview
- Forecast cards
- Visual presentation for quick reading

The UI is optimized for readability and fast checking.

:contentReference[oaicite:3]{index=3}

---

## Air Quality Index

Integrated AQI support includes:

- AQI scale
- PM2.5
- PM10
- NO₂
- SO₂
- O₃
- CO

Useful for checking urban air conditions beyond standard weather.

:contentReference[oaicite:4]{index=4}

---

## Weather Alerts

Built-in alert generation based on live conditions:

Examples:

- Heat warning
- Strong wind alert
- Humidity alert
- Rain advisory
- Thunderstorm warning

This provides quick practical guidance rather than only raw data.

:contentReference[oaicite:5]{index=5}

---

## City Coverage

Includes a built-in dataset of Indian cities with:

- State
- Population
- Latitude
- Longitude

Supports filtering by:

- State
- Population size
- Dropdown selection

This makes city lookup efficient even without external search.

:contentReference[oaicite:6]{index=6}

---

## Analytics

Includes chart-based views for weather interpretation.

Visual sections include:

- Comparative city analysis
- Hourly weather views
- Trend graphs
- Forecast charts

Built for quick understanding, not just raw numbers.

---

## Technology

Built using:

- HTML5
- CSS3
- Vanilla JavaScript
- Chart.js
- OpenWeather API

No frameworks used.

---

## Project Structure

```text
project/
│
├── weather.html
└── README.md
