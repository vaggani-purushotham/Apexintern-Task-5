# Apexintern-Task-5

# Weather App

A responsive web application that shows current weather and a 5-day forecast for any city using the OpenWeatherMap API. It dynamically updates the background and includes smooth animations for weather info and icons.

# Features

Get current weather by city name

Display temperature, humidity, wind speed, and weather description

Dynamic background based on weather conditions (sunny, cloudy, rainy, snowy, foggy, etc.)

5-day forecast with icons and weather info

Smooth fade-in and bounce animations

Responsive design for mobile and desktop

Error handling for invalid city names



# Technologies Used

HTML5

CSS3 (animations, gradients, responsive design)

JavaScript (fetch API, DOM manipulation)

OpenWeatherMap API

# How to Run the Project

⚠️ Important: Opening index.html directly via the file system may cause API requests to fail due to CORS. Use Live Server or a local HTTP server.

# Option 1: Using Live Server in VS Code

Open VS Code and install the Live Server extension (by Ritwick Dey).

Open your project folder in VS Code.

Open index.html.

Right-click → Open with Live Server.

Your app will open in the browser at an address like:

http://127.0.0.1:5500/index.html


Enter a city name and click Get Weather to see the results.

# Option 2: Using Python Local Server

Open terminal/command prompt in your project folder.

Run the following command (requires Python installed):

python -m http.server


Open your browser and go to:

http://localhost:8000


Your app should load, and API calls will work correctly.

# Notes

Replace the API key in script.js with your own OpenWeatherMap API key.

Make sure you have an active internet connection for the API calls.

Works best on modern browsers like Chrome, Firefox, and Edge.

# Future Improvements

Add geolocation support to detect the user’s current location.

Add unit toggle (Celsius ↔ Fahrenheit).

Include more detailed weather info like sunrise/sunset, pressure, or UV index.

Add caching for API results to reduce repeated requests.
