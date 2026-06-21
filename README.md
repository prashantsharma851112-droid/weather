# 🌤️ WeatherNow

A responsive weather web application that provides real-time weather data for any city in the world using the OpenWeatherMap API.

🔗 **Live Demo:** [prashantsharma851112-droid.github.io/weather](https://prashantsharma851112-droid.github.io/weather)

---

## ✨ Features

- 🔍 **Real-time Weather Search** — Get current weather for any city worldwide
- 🌡️ **Celsius / Fahrenheit Toggle** — Switch temperature units instantly
- 🕐 **Recent Searches** — Last 6 searches saved locally using localStorage
- 🌅 **Detailed Weather Info** — Sunrise, Sunset, Cloud Cover, Wind Direction
- 💧 Humidity, Wind Speed, Visibility, Pressure stats
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop
- 🎨 **Glassmorphism UI** — Animated gradient background with blur effects
- ⚡ **Error Handling** — Clear messages for invalid city or API errors

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, Animations, Glassmorphism |
| Vanilla JavaScript | Logic, DOM Manipulation |
| OpenWeatherMap API | Real-time weather data |
| localStorage | Recent search history |
| GitHub Pages | Deployment |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/prashantsharma851112-droid/weather.git
cd weather
```

### 2. Get a free API key
- Go to [openweathermap.org](https://openweathermap.org/api)
- Sign up for a free account
- Copy your API key from the dashboard

### 3. Add your API key
Open `index.html` and find this line:
```javascript
const API_KEY = "YOUR_API_KEY_HERE";
```
Replace `YOUR_API_KEY_HERE` with your actual API key.

### 4. Open in browser
```bash
# Simply open index.html in any browser
open index.html
```

---

> Search any city and get instant weather results with a beautiful glassmorphism UI.

---

## 📁 Project Structure

```
weather/
│
├── index.html        # Main application file (HTML + CSS + JS)
└── README.md         # Project documentation
```

---

## 🌐 API Reference

This project uses the **OpenWeatherMap Current Weather API**:

```
GET https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```

**Free tier includes:** 60 calls/minute, 1,000,000 calls/month

---

## 👨‍💻 Author

**Prashant Sharma**
- GitHub: [@prashantsharma851112-droid](https://github.com/prashantsharma851112-droid)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
