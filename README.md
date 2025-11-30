# 🌤️ SkyScope — Modern Weather Web App

SkyScope is a clean, fast, and responsive weather application built with **React.js + Vite**.  
It delivers real-time weather data with dynamic visuals that match the current conditions, offering a smooth and minimal user experience.

---

## ✨ Features

- 🌡️ **Real-time weather updates**
- 🔎 **Search weather by any city**
- 📍 **Check your current location's weather in one click**
- 🎨 **Dynamic backgrounds & icons** based on real weather conditions
- 📱 **Fully responsive & minimal UI**
- ⚡ Powered by **OpenWeather API**

---

## 🚀 Tech Stack

- **React.js** (UI)
- **Vite** (development tooling + fast bundling)
- **OpenWeather API** (live weather data)

---

## 📦 Install & Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-username/SkyScope.git
cd SkyScope
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up your OpenWeather API key  
Create a `.env` file in the project root:

```
VITE_WEATHER_API_KEY=your_api_key_here
```

### 4. Start the development server
```bash
npm run dev
```

Now open the local URL shown in your terminal (usually `http://localhost:5173`).

---

## 🌍 API Information

SkyScope uses the **OpenWeather API** to retrieve real-time weather info.

Example endpoint:
```
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}
```

---

## 📁 Project Structure

```
SkyScope/
│── public/
│── src/
│   ├── components/
│   ├── assets/
│   ├── index.css
│   ├── App.jsx
│   └── main.jsx
│── index.html
│── package.json
│── README.md
```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you found this project useful, please consider giving it a **star** ⭐ on GitHub!

