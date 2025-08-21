# 🌦️ Node Weather App

A simple weather application built with **Node.js**, **Express**, and **Handlebars (hbs)**.  
It fetches real-time weather data using APIs and displays it in a clean web interface.  

🔗 **Live Demo**: [Node Weather App](https://node-weather-app-vzlr.onrender.com/)  

---

## ✨ Features

- 🌍 Search weather by city name  
- 📍 Get current location weather (using geocoding)  
- 🌡️ Displays temperature, weather conditions, and more  
- ⚡ Fast and lightweight with Express.js  
- 🎨 Handlebars for templating with dynamic content

## 📂 Project Structure

Node-Weather-App/
│
├── public/ # Static frontend assets (CSS, JS, Images)
│ └── css/
│ └── styles.css # Custom styles
│
├── src/
│ ├── app.js # Main server entry point
│ ├── utils/
│ │ ├── forecast.js # Fetches weather data from API
│ │ └── geocode.js # Converts location name into coordinates
│
├── templates/ # Handlebars templates
│ ├── views/ # Dynamic pages (index.hbs, about.hbs, help.hbs)
│ └── partials/ # Shared UI components (header, footer, etc.)
│
├── package.json
└── README.md

🛠️ Tech Stack

**Node.js + Express.js
**
**Handlebars (hbs)
**
**Weather API (forecast & geocode utils)
**
CSS for styling
