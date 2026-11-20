# 🌦️ Weather Forecast Application

## 📌 Project Overview

The Weather Forecast Application is a Python-based project that retrieves real-time weather information and provides a five-day weather forecast for any city using the OpenWeatherMap API.

Users can enter a city name and view important weather details through a simple command-line interface.

## 🚀 Features

- Search weather information by city name.
- Display current temperature in Celsius.
- Display feels-like temperature.
- Show humidity percentage.
- Display weather conditions.
- Show wind speed.
- Provide a five-day weather forecast.
- Handle invalid city names and network errors.

## 🛠️ Technologies Used

- Python 3
- Requests Library
- OpenWeatherMap API
- JSON
- VS Code

## 📂 Project Structure

```text
weather_app/
│
├── weather.py
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project folder

```bash
cd weather_app
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Create an account at [https://openweathermap.org/api](https://openweathermap.org/api) and generate an API key.

Add your API key in `weather.py`:

```python
API_KEY = "YOUR_API_KEY"
```

**Note:** Never upload your actual API key to GitHub.

### 5. Run the application

```bash
python weather.py
```

## 📊 Sample Output

```text
Enter city name: Hyderabad

===== WEATHER REPORT =====
City: Hyderabad
Country: IN
Temperature: 28.5 °C
Feels Like: 30.2 °C
Humidity: 65 %
Weather: scattered clouds
Wind Speed: 3.5 m/s
==========================

===== 5 DAY WEATHER FORECAST =====
```

*Sample values are for demonstration purposes.*

## 🔗 API Used

OpenWeatherMap API: [https://openweathermap.org/api](https://openweathermap.org/api)

## 🎯 Learning Outcomes

- Learned how to integrate third-party APIs with Python.
- Practiced HTTP GET requests.
- Understood JSON data handling.
- Used dictionaries and loops to extract API responses.
- Implemented exception handling.
- Learned to build a real-time data-based Python application.

