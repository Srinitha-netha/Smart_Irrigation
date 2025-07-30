
# 🌱 Smart Irrigation System 💧

This project is a **Smart Sprinkler System** that uses a machine learning model to predict the ON/OFF status of sprinklers based on sensor data. Built with **Streamlit**, it provides an interactive UI for users to input scaled sensor values and view real-time predictions for 20 irrigation parcels.

## 🚀 Features

- Predict sprinkler activity for 20 zones using sensor data
- Interactive UI for inputting scaled sensor values (0–1)
- Visual status display: ON/OFF for each sprinkler
- Model trained using historical irrigation data
- Powered by `joblib`, `scikit-learn`, and `Streamlit`

## 🧠 Machine Learning

The model was trained on a dataset of soil and environmental sensor readings. It outputs binary values (0 = OFF, 1 = ON) indicating whether each sprinkler should be active.

Model: `Farm_irrigation_System.pkl`  
Framework: `scikit-learn`

## 📦 Project Structure

