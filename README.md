# 🌫️ Air Quality Checker Web App

A simple and interactive web application that allows users to check real-time air quality data using latitude and longitude. This project fetches pollution data such as AQI, CO, PM2.5, PM10, and more using an external API.

---

## 🚀 Features

* 📍 Enter Latitude & Longitude to get air quality
* 🌫️ Displays AQI (Air Quality Index)
* 🧪 Shows pollutant levels:

  * CO (Carbon Monoxide)
  * NO₂ (Nitrogen Dioxide)
  * O₃ (Ozone)
  * PM2.5 & PM10 (Particulate Matter)
  * SO₂ (Sulfur Dioxide)
* 🎨 Clean and responsive UI
* ⚡ Real-time API data fetching

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* RapidAPI (Air Quality API)

---

## 📸 Sample Output

Example for coordinates:

Latitude: 17.3948
Longitude: 78.5420

Output:

* AQI: 156 (Unhealthy)
* CO: 172
* PM2.5: 60
* PM10: 101

---

## 🔧 How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/air-quality-checker.git
   ```

2. Navigate to the project folder:

   ```bash
   cd air-quality-checker
   ```

3. Open `index.html` in your browser

---

## 🔑 API Setup (Important)

This project uses an API from RapidAPI.

Steps:

1. Go to RapidAPI and subscribe to an Air Quality API
2. Copy your API key
3. Replace it in your `index.js` file:

```javascript
headers: {
  "X-RapidAPI-Key": "YOUR_API_KEY",
  "X-RapidAPI-Host": "air-quality.p.rapidapi.com"
}
```

⚠️ Note: If you see a **403 error**, it means you are not subscribed to the API.

---

## 📊 AQI Categories

| AQI Range | Category                          |
| --------- | --------------------------------- |
| 0–50      | Good ✅                            |
| 51–100    | Moderate ⚠️                       |
| 101–150   | Unhealthy for Sensitive Groups 😷 |
| 151–200   | Unhealthy 🚫                      |
| 201+      | Very Unhealthy ❌                  |

---

## 📌 Future Improvements

* 📱 Mobile responsiveness enhancement
* 📍 Auto-detect current location
* 📈 Graphs for pollution trends
* 🌍 Map integration

---

## 👨‍💻 Author

Ganesh Aidapu
B.Tech Student

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

