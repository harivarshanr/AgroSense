# 🌾 AgroSense – Smart Crop Recommendation System

AgroSense is a smart agriculture platform that uses **IoT sensors** and **machine learning** to help farmers identify the most suitable crop to cultivate based on real-time soil and weather conditions.

This project integrates data from sensors like **pH, soil moisture, humidity, and NPK** levels and uses a trained ML model to provide crop recommendations. It features a React-based frontend and a Python Flask backend for seamless interaction and predictions.

---

## 🚜 IoT Sensors Used

The system collects data from the following sensors:

- 🌡️ **Soil Moisture Sensor** – Measures the volumetric water content of the soil.
- 🔬 **pH Sensor** – Determines soil acidity/alkalinity.
- 🌫️ **Humidity Sensor** – Detects environmental humidity levels.
- 🌿 **NPK Sensor** – Detects the nutrient concentration:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)

---

## 🧠 Features

- Real-time data collection via IoT devices
- ML-based prediction of suitable crops
- Clean UI to input sensor data
- Built with React (frontend) and Flask (backend)
- Simple deployment and easy-to-extend design

---

## 🛠️ Tech Stack

| Layer       | Technology        |
|-------------|-------------------|
| Frontend    | React.js          |
| Backend     | Flask (Python)    |
| ML Model    | Scikit-learn      |
| Data Source | Agricultural datasets |
| Sensors     | IoT Devices (pH, Moisture, NPK, Humidity) |

---

## 🚀 Getting Started

Follow these steps to set up and run the AgroSense project on your local machine.

### ✅ 1. Clone the Repository

```bash
git clone https://github.com/harivarshanr/AgroSense.git
cd AgroSense
```

### ✅ 2. Set Up the Backend (Flask API)

Make sure you have Python 3 installed. Then:

```bash
cd backend

# Optional: create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start the Flask server
python app.py
```

Visit: [http://localhost:5000](http://localhost:5000)

### ✅ 3. Set Up the Frontend (React)

Open a new terminal:

```bash
cd frontend
npm install
npm start
```

Visit: [http://localhost:3000](http://localhost:3000)

### ✅ 4. Test the App

1. Enter sensor values (pH, N, P, K, humidity, moisture).  
2. Click on **Predict**.  
3. View the crop recommendation output.

