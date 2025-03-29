# ☀️ Weather App 🌧️

A simple Weather App that provides real-time weather updates for any city. It fetches data from the OpenWeather API and displays essential weather details, including temperature, humidity, wind speed, and sunrise/sunset times. 

## 🚀 Live Demo
[🔗 Click here to view the live demo]( https://glathika.github.io/Weather_App/) *(Replace with your actual deployment link)*

## ✨ Features
✅ Get real-time weather updates for any city 🌍
✅ Display temperature 🌡️, humidity 💧, wind speed 🌬️, and pressure ⚖️
✅ Show sunrise 🌅 and sunset 🌄 times
✅ 7-day weather forecast 📅
✅ Dynamic background changes for day 🌞 and night 🌙 modes
✅ Interactive map integration for the selected city 🗺️

## 🛠 Technologies Used
- ⚡ HTML
- 🎨 CSS
- 🖥️ JavaScript
- ☁️ OpenWeather API
- 📍 Google Maps Embed API
- 🕒 Moment.js

## 🔍 How to Use
1. Enter the name of a city in the search bar. 📌
2. Click on the **🔎 Search** button to get the latest weather details.
3. View additional details like humidity, wind speed, and pressure. 📊
4. Toggle between **☀️ Day Mode** and **🌙 Night Mode** for different themes.
5. Check the **📅 7-day weather forecast** at the bottom.

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```
3. Open `index.html` in your browser. 🌐

## 🔑 API Configuration
This app uses the OpenWeather API. To make it work:
1. Get an API key from [🔗 OpenWeather](https://openweathermap.org/).
2. Replace `YOUR_API_KEY` in `script1.js`:
   ```javascript
   let res = await fetch(`https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=YOUR_API_KEY&units=metric`);
   ```

## 📸 Screenshots
*(Add screenshots of your app here)*

## 📜 License
This project is licensed under the MIT License.

