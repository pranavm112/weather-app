# 🌦️ Weather App

A sleek, responsive weather application that allows users to view real-time weather data based on their current location or by searching for any city in the world.

---

## ✨ Features

- 📍 **Your Weather** – Get weather data using browser location (Geolocation API)
- 🔍 **Search Weather** – Search weather by city name
- 🌡️ Temperature, 💨 Wind Speed, 💧 Humidity, ☁️ Cloudiness
- 🧭 Country flags and weather icons
- 🔒 Secure API setup with `config.js` (not included in the repository)
- 💻 Fully responsive for mobile, tablet, and desktop

---

## 📁 Folder Structure

Weather_App/
├── assets/ # Icons & background image
├── index.html # Main HTML file
├── index.js # JavaScript logic
├── styles.css # Styling
├── config.js # API key (gitignored)
└── .gitignore # Ignores config.js and other local files



---

## ⚙️ How to Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/pranavm112/Weather-App.git
   cd Weather-App
   


Create a config.js file in the root of the project:

2. Create a config.js file in the root of the project:
    const API_KEY = "your_openweather_api_key";

3. Open index.html in your browser

💡 Make sure you’re connected to the internet so external API and icons can load properly.


🔐 Security
config.js is included in .gitignore to protect your API key.

Never share your actual API key in public repositories.


