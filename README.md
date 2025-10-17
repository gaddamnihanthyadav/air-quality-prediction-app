# air-quality-prediction-app
AI-powered web app that predicts air quality using sensor data and machine learning, with health alerts and safe route suggestions.
# 🌍 Air Quality Prediction App

This project is a full-stack AI-powered web application that predicts Air Quality Index (AQI) using real-time sensor data and machine learning. It provides hyperlocal AQI forecasts, health alerts, and safe route suggestions to help users make informed decisions about outdoor activities.

## 🔧 Features

- Predict AQI using PM2.5, PM10, NO₂, CO, and O₃ values
- Machine learning model trained on historical sensor data
- Flask backend API for AQI prediction
- Streamlit frontend for user interaction
- Health alerts based on AQI thresholds
- Ready for deployment on Render and Streamlit Cloud

## 🚀 Tech Stack

- Python, Flask, Streamlit
- Scikit-learn, Pandas, NumPy
- Joblib for model serialization
- Render for backend deployment
- Streamlit Cloud for frontend hosting

## 📁 Folder Structure

## 🧠 How It Works

1. Train a Random Forest model using historical AQI data
2. Serve predictions via a Flask API (`/predict`)
3. Collect user input through a Streamlit interface
4. Display predicted AQI and health guidance

## 📦 Getting Started

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Train the model: run `notebooks/train_model.ipynb`
4. Start the backend: `python backend/app.py`
5. Launch the frontend: `streamlit run frontend/streamlit_app.py`

## 🌐 Deployment

- Backend: Deploy `app.py` to Render as a Web Service
- Frontend: Deploy `streamlit_app.py` to Streamlit Cloud
