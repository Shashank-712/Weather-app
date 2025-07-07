# 🌦️ Weather App

A beginner-friendly **Django-based weather app** that allows users to enter a city name and retrieve current weather data using the **OpenWeatherMap API**. Built with Python, Django, HTML, and Bootstrap.

---

## 🚀 Features

- 🔍 Search for real-time weather by city name
- 🌡️ View temperature, weather condition, and descriptions
- 🖼️ Dynamic weather icons based on API data
- ✅ Error handling for invalid or empty inputs
- 🎨 Responsive frontend using Bootstrap

---

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, Bootstrap
- **Weather API:** OpenWeatherMap
- **Database:** SQLite (for development)

---

## 📁 Project Structure
Weathering App/
├── core/ # Django project settings
├── weather/ # Weather app (views, urls, templates)
├── templates/ # HTML templates
├── .env/ # Virtual environment (not tracked)
├── .gitignore # Git ignore rules
├── manage.py # Django management script
└── db.sqlite3 # SQLite database (local)


---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Shashank-712/Weather-app.git
cd Weather-app
```
###2. Create & Activate a Virtual Environment
```
python -m venv .env
source .env/Scripts/activate   # On Windows
# or
source .env/bin/activate       # On Mac/Linux
```
###3. Install Requirements
```
pip install -r requirements.txt
```
###4. Add Your OpenWeatherMap API Key
Create a .env file in the root folder and add:
```
WEATHER_API_KEY=your_openweathermap_api_key_here
```
Then update your views.py to use:
```
import os
api_key = os.environ.get('WEATHER_API_KEY')
```
(Or use python-decouple for better practice.)
###5. Run the App
```
python manage.py runserver
```
Open your browser and go to:
👉 http://127.0.0.1:8000/

📌 Notes
-Make sure .env is included in your .gitignore (✅ already done)
-This app is for educational/demo purposes and uses SQLite for simplicity
-Replace your_openweathermap_api_key_here with your actual API key

🙌 Author
Made with 💻 by Shashank Rawat👹
🔗 github.com/Shashank-712
