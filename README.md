# hackathon
# AgriConnect – AI-Powered Crop Recommendation & Yield Prediction

AgriConnect is an AI-powered advisory platform for farmers and agricultural officers.  
It uses **ANN (Artificial Neural Networks)** to recommend the most suitable crop based on soil, rainfall, temperature, and other features — and predicts the expected yield.  
It also includes a **rule-based FAQ system** to answer common agricultural queries.

---

## Features
- **Crop Recommendation** – Predicts the best crop for given soil & climate conditions.
- **Yield Prediction** – Estimates tonnes per hectare for the recommended crop.
- **Hybrid AI + Rule-based System** – Combines ML predictions with agricultural knowledge.
- **Multilingual QA** – Supports English and simple Hindi terms for FAQ queries.
- **FastAPI Backend (optional)** – For serving predictions via API.
- **Streamlit Frontend** – For interactive web app.
- **Retraining Ready** – Periodic retraining with new data.

---

## Project Structure
├── data/ # Synthetic or real agricultural datasets
├── models/ # Trained ML models & metadata
├── agriconnect_streamlit.py # Streamlit frontend app
├── agriconnect_api.py (optional) # FastAPI backend (if used)
├── README.md # Project documentation
└── requirements.txt # Python dependencies

