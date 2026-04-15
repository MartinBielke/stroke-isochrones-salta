# 🧠 Stroke Network Isochrone Analysis – Salta (Argentina)

This project analyzes **geographic accessibility to stroke care (ACV)** in Salta, Argentina, using network-based isochrones and population data.

It combines geospatial analysis, public health insight, and data science to identify **coverage gaps and risk areas** in emergency stroke response.

---

## 🚀 Project Overview

Stroke treatment is highly time-sensitive. This project models:

* ⏱ Travel times to hospitals using real road networks
* 🗺 Isochrones (1h, 2h, 4h accessibility zones)
* 👥 Population coverage within each time window
* ⚠️ Risk areas based on limited access and socioeconomic indicators

The goal is to support **better decision-making in healthcare planning**.

---

## 🧰 Tech Stack

* 🐍 Python
* 🌍 OSMnx
* 🧭 NetworkX
* 🗺 GeoPandas
* 📊 Pandas
* 📍 Folium (interactive maps)

---

## 📊 Features

* Extraction of road networks from OpenStreetMap
* Travel-time modeling with realistic ambulance speeds
* Isochrone generation from hospital locations
* Spatial population analysis
* Risk modeling (accessibility + socioeconomic variables)
* Interactive visualization

---

## 📁 Project Structure

```
├── isochrones.ipynb      # Main notebook
├── data/                 # Input datasets
├── outputs/              # Generated maps and results
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/stroke-isochrones-salta.git
```

2. Install dependencies:

```bash
pip install osmnx geopandas networkx folium pandas
```

3. Open the notebook:

```bash
jupyter notebook
```

Nota para ejecutar: Asegurate de ejecutar jupyter notebook dentro de la carpeta raíz del repositorio (la que contiene isochrones.ipynb y las carpetas data/, outputs/).

---

## 🌎 Results

The notebook produces interactive maps showing:

* Accessibility zones to stroke centers
* Population coverage
* High-risk underserved areas

These outputs can support:

* Health policy decisions
* Resource allocation
* Emergency network optimization

---

## 👤 Author

**Martin Bielke**

* 🎓 PhD in Philosophy
* 🇩🇪 German Teacher & Translator
* 🤖 Data & AI Projects in Healthcare
* 🎧 Electronic Music Producer

---

## 💡 Future Work

* Integration with real-time hospital capacity data
* WhatsApp/Telegram bot for live updates (in development)
* Machine learning for predictive risk modeling

---
