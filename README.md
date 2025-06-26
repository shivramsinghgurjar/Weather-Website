
# 🌦️ Weather Website

Welcome to the **Weather Web**, a simple yet beautiful weather forecast application built using **HTML**, **CSS**, and **JavaScript**. It fetches real-time weather data using the **OpenWeatherMap API** and displays the temperature and description of the weather for any city entered by the user.

🚀 [Live Demo](https://shivramsinghgurjar.github.io/Weather-Website/)

![App Screenshot](https://shivramsinghgurjar.github.io/Weather-Website/Images_And_Video/weather-screenshot.png)

---

## 🧰 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- OpenWeatherMap API

---

## 📁 Project Structure

```
Weather-Website/
│
├── Images_And_Video/       # Contains background images/videos used in UI
├── index.html              # Main HTML file
├── style.css               # Styling for the page
├── script.js               # Core JS logic including API integration
└── README.md               # Project documentation
```

---

## 🔧 Features

- 🌐 Real-time weather fetching for any city.
- 📍 Displays:
  - City name
  - Temperature (°C)
  - Weather description
- 🎨 Stylish user interface with a sky/cloud background.
- 🔎 Input field to search weather by city name.
- 🌩️ Error handling for invalid city names or API issues.

---

## 📦 How to Run the Project Locally

### ✅ Prerequisites

Before starting, make sure you have:

- A modern web browser (Chrome, Edge, Firefox)
- A text editor (VS Code recommended)
- [OpenWeatherMap API key](https://openweathermap.org/api)

---

### 📥 Steps to Setup

1. **Clone the Repository**

```bash
git clone https://github.com/shivramsinghgurjar/Weather-Website.git
cd Weather-Website
```

2. **Get Your OpenWeatherMap API Key**

- Go to [OpenWeatherMap](https://openweathermap.org/)
- Sign up / Log in
- Navigate to **API Keys** section from the dashboard
- Copy your API key

3. **Insert the API Key**

- Open the `script.js` file
- Locate the section where the API URL is defined:
```js
const apiKey = "YOUR_API_KEY_HERE";
```
- Replace `"YOUR_API_KEY_HERE"` with your actual key.

✅ Example:
```js
const apiKey = "a1b2c3d4e5f6g7h8";
```

4. **Open the App**

- Open the `index.html` file in your browser.
- You should see the Weather Web interface.
- Enter any city name and click **Get Weather**.

---

## 🌐 How it Works

- When the user enters a city and clicks "Get Weather", the `fetchWeather()` function in `script.js` makes an API call to OpenWeatherMap.
- The returned data is parsed to extract temperature and weather description.
- These details are dynamically inserted into the HTML and shown on the screen.

---

## 📸 Screenshots

### Main Interface  
![Weather Web Interface](https://shivramsinghgurjar.github.io/Weather-Website/Images_And_Video/weather-screenshot.png)

---

## ⚠️ Error Handling

- If the city name is incorrect or not found, the application shows an alert using JavaScript.
- Make sure to enter correct spellings and check your internet connection if weather data fails to load.

---

## ✨ Future Enhancements

- Add temperature units toggle (°C/°F)
- Display more detailed weather info (humidity, wind speed, etc.)
- Add location-based weather using Geolocation API
- Make it responsive for mobile view

---

## 👨‍💻 Author

**Shivram Singh Gurjar**

- 🔗 [GitHub Profile](https://github.com/shivramsinghgurjar)
- 💼 B.Tech CSE @ Sharda University

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repo and submit a pull request.

---

## 📝 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).
