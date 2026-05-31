# 🌤️ Atmosphere — Weather Dashboard

A beautiful, animated weather dashboard built with **pure HTML, CSS & JavaScript**. It fetches real-time weather data from the OpenWeatherMap API and renders immersive animated scenes that change dynamically based on the current weather conditions.

![Atmosphere Weather Dashboard](https://img.shields.io/badge/Weather-Dashboard-7eb8f7?style=for-the-badge&logo=cloudflare&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## ✨ Features

- 🌍 **Search any city** worldwide for live weather data
- 🌡️ **°C / °F toggle** — switch between Celsius and Fahrenheit instantly
- 🎨 **Dynamic animated scenes** — sun, rain, snow, thunderstorm, fog & more
- ⏱️ **Hourly forecast** for the next 24 hours
- 📅 **5-day forecast** with high/low temperatures
- 📍 **Auto geolocation** — detects your location on first load
- 💨 Displays **Humidity, Wind Speed, Visibility & Pressure**
- 📱 **Fully responsive** — works on mobile and desktop
- 🌙 **Day/Night sky** — backdrop changes based on time of day
- ⚡ Zero dependencies — no frameworks, no build tools

---

## 🖼️ Weather Scenes

| Condition | Scene |
|-----------|-------|
| ☀️ Clear (Day) | Animated glowing sun + blue sky |
| 🌙 Clear (Night) | Twinkling stars on deep navy |
| ⛅ Partly Cloudy | Drifting clouds with partial sun |
| ☁️ Overcast | Heavy cloud layer |
| 🌧️ Rain | Falling raindrops + dark sky |
| ⛈️ Thunderstorm | Lightning bolts + heavy rain |
| ❄️ Snow | Falling snowflakes |
| 🌫️ Fog / Mist | Layered fog strips |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/atmosphere-weather-dashboard.git
cd atmosphere-weather-dashboard
```

### 2. Get a free OpenWeatherMap API key

1. Sign up at [openweathermap.org](https://openweathermap.org/api) (free)
2. Go to **API Keys** in your dashboard
3. Copy your key (activates in ~10 minutes)

### 3. Add your API key

Open `index.html` and find this line near the top of the `<script>` block:

```js
const API_KEY = 'YOUR_API_KEY'; // ← paste your key here
```

Replace `'YOUR_API_KEY'` with your actual key.

### 4. Open in browser

Simply open `index.html` in any modern browser — no server or build step needed!

```bash
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

---

## 🗂️ Project Structure

```
atmosphere-weather-dashboard/
├── index.html      # App markup + all JavaScript logic
├── style.css       # Styles, animations & weather scene effects
└── README.md       # This file
```

---

## 🔌 API Used

- **[OpenWeatherMap](https://openweathermap.org/api)** — Current Weather API + 5 Day / 3 Hour Forecast API
  - Free tier: 60 calls/minute, more than enough for personal use
  - Endpoints used: `/weather` and `/forecast`

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & semantic markup |
| CSS3 | Animations, glassmorphism UI, responsive layout |
| Vanilla JS | API calls, DOM manipulation, scene rendering |
| Google Fonts | DM Sans + DM Serif Display |
| OpenWeatherMap API | Live weather & forecast data |

---

## 📸 Screenshots

> Search any city and watch the sky transform in real time!

---

## 🤝 Contributing

Pull requests are welcome! Feel free to:
- Add new weather scenes or animations
- Improve mobile responsiveness
- Add more weather stats (UV index, sunrise/sunset, etc.)
- Improve accessibility

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ using pure HTML, CSS & JS</p>
