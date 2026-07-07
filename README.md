# 🚚 CargoPath – Smart Cargo Routing System

CargoPath is an AI-powered logistics and route optimization platform that helps transporters choose the safest and most profitable routes for fragile and high-value cargo. The application considers road damage, cargo fragility, transportation costs, and estimated profits to recommend optimal delivery paths.

---

## ✨ Features

- 🛣️ Damage-aware route optimization using Dijkstra's Algorithm
- 📦 Cargo-specific route recommendations
- 💰 Profit estimation and transportation cost analysis
- 🤖 AI-generated route explanations using Google Gemini
- 👤 User authentication (Sign Up / Sign In)
- 📜 Route history tracking
- 📊 Route statistics dashboard
- 📧 Contact form with email support
- 🌐 Responsive modern UI built with HTML, CSS, and JavaScript

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- SQLite

### AI
- Google Gemini API

### Algorithms
- Damage-aware Dijkstra Algorithm
- Profit Analysis
- Alternative Route Generation

---

## 📁 Project Structure

```
CargoPath/
│
├── app.py                 # Main Flask application
├── algorithm.py           # Route optimization algorithms
├── database.py            # Database operations
├── requirements.txt
│
├── data/
│   ├── cargo_data.py
│   └── graph_data.py
│
├── templates/
│   ├── index.html
│   ├── route.html
│   ├── history.html
│   ├── signin.html
│   ├── signup.html
│   ├── profile.html
│   ├── about.html
│   └── contact.html
│
├── static/
│   ├── style.css
│   └── app.js
│
└── cargopath.db
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/CargoPath.git
cd CargoPath
```

### 2. Create a virtual environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

```bash
python app.py
```

The application will start at:

```
http://127.0.0.1:5000
```

---


## 🧠 Route Optimization Process

1. Select cargo type.
2. Choose source and destination.
3. CargoPath analyzes:
   - Road roughness
   - Cargo fragility
   - Transportation distance
   - Fuel and transportation cost
   - Expected profit
4. The safest and most profitable route is recommended.
5. Google Gemini generates a human-readable explanation for the chosen route.

---



## 🚀 Future Improvements

- Live traffic integration
- Weather-based routing
- GPS navigation
- Real-time shipment tracking
- Admin dashboard
- Predictive maintenance alerts
- Mobile application
- Multi-language support

---

## 👨‍💻 Developed By

**Vaisshnave**
**Kashish**

---

