# 🌦 Project: Weather API

### Goal: Enable your user to enter a city + country and return the temperature in Fahrenheit

### How to submit your code for review:

- Fork and clone this repo
- Create a new branch called answer
- Checkout answer branch
- Push to your fork
- Issue a pull request
- Your pull request description should contain the following:
  - (1 to 5 no 3) I completed the challenge
  - (1 to 5 no 3) I feel good about my code
  - Anything specific on which you want feedback!

Example:
```
I completed the challenge: 5
I feel good about my code: 4
I'm not sure if my constructors are setup cleanly...
```
# Live Weather Lookup App

A lightweight web application that allows users to search for any city or region to instantly get the current weather conditions, temperature, and local location details using WeatherAPI.

---

## Features

- **Location Search:** Accepts city names, regions, or location inputs.
- **Current Temperature:** Displays local temperatures in Fahrenheit ($^\circ\text{F}$).
- **Weather Condition Icons:** Dynamically displays the current weather icon directly from WeatherAPI.
- **Detailed Location Info:** Shows the matched location name, region/state, country, and weather description.

---

## API Used

- **WeatherAPI Current Weather API:** `http://api.weatherapi.com/v1/current.json`

---

## How It Works

1. The user enters a location into `#locationVal` and clicks the `#locationBtn` button.
2. The application requests current weather data for that query from WeatherAPI.
3. Upon receiving the response, it extracts:
   - Temperature in Fahrenheit (`temp_f`)
   - Weather condition text and condition icon URL (`condition.text`, `condition.icon`)
   - Location details (`name`, `region`, `country`)
4. The application updates the target DOM elements to display the full weather report.

---
<img width="2825" height="1565" alt="image" src="https://github.com/user-attachments/assets/1bb66c15-1807-4661-8090-ec91cc51fe2b" />
