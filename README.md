# 🌊 Kedal Kaval – Enhancing Efficiency and Sustainability in Tamil Nadu’s Coastal Fishing Practices

A smart, AI-driven coastal fisheries management system that empowers local fishing communities in Tamil Nadu by improving efficiency, ensuring regulatory compliance, and promoting sustainability.

---

## 📌 Project Summary

**Kedal Kaval** is a Streamlit-based web application that combines AI-powered fish detection with real-time environmental monitoring and government regulation enforcement to support responsible marine fishing in Tamil Nadu.

Streamlit : https://kadal-kaval.streamlit.app/


---

## 🐟 Key Features

### 🎣 Fish Detection with YOLOv8
- Upload coastal images to detect fish species or boats using YOLOv8.
- Displays bounding boxes, confidence levels, and species information.

### 🌐 Location-Aware Coastal Intelligence
- Automatically detects the user’s location (within Tamil Nadu's coastline).
- Shows real-time weather and ocean conditions using OpenWeather & IMD APIs.

### 🚫 Fishing Ban Awareness
- System checks for active seasonal bans (e.g., June 15 – August 15).
- Displays warnings and adjusts recommendations accordingly.

### 🌱 Sustainable Fishing Metrics
- Fuel-based CO₂ emissions calculator for eco-friendly planning.
- AI suggestions on ideal fishing time and location based on weather/ocean data.

### 📈 Historical Catch Trends
- Visualizes fishing trends using logs (`catch_logs.json`) or simulated data.

### 🗺️ Interactive Coastal Mapping
- Uses `folium` to map current location and TN’s fishing boundary polygon.

### 🌐 Bilingual Interface
- Supports **English** and **தமிழ் (Tamil)** UI options.

---

## 🛠️ Tech Stack
- Frontend/UI: Streamlit

- AI Model: YOLOv8 (Ultralytics)

- Mapping: Folium, Shapely

- APIs: OpenWeather, IMD, Geocoder

- Data Processing: Pandas, NumPy

- Visualization: Plotly

- Image Handling: Pillow

---

## 🌍 Impact Goals

- Reduce overfishing with smart ban enforcement

- Promote fuel-efficient trips and CO₂ awareness

- Support Tamil-speaking fisherfolk with local language access

- Empower data-driven decision making at sea

---

## 📈 Future Scope
- Blockchain traceability for catch

- Mobile app integration with GPS

- Government dashboard for regulation enforcement

- Smart pricing based on catch volume and weather

---

## 🙌 Credits
- Developed by Arps09 (Team: Griffin)
- For Google Solution Challenge 2025
- Inspired by the needs of Tamil Nadu’s coastal communities

---

## 🗂️ Repository Structure

```bash
.
├── README.md                # Documentation
├── fish_detection.py        # Streamlit app (main code)
├── yolov8n.pt               # YOLOv8 model weights
├── catch_logs.json          # Catch log history
├── tn_regulations.json      # Government fishing regulations
├── requirements.txt         # Python dependencies
├── apt-packages.txt         # APT packages (for deployment)
├── runtime.txt              # Runtime version for Streamlit

---



