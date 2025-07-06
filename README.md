# 🌊 Final Project – Water Quality Prediction (Polished & App-Enabled Version)

This final version of the **Water Quality Prediction** project demonstrates a complete machine learning pipeline: from data preprocessing and multi-target regression to visualizations and an interactive web app using Streamlit. This project was developed as part of the **AICTE Virtual Internship** sponsored by **Shell**, conducted by **Edunet Foundation** in **June 2025**.

---

## 🎯 Objective

To build a scalable and user-friendly predictive model that estimates key water pollutant levels for a selected monitoring station and year, and makes the results accessible through a Streamlit-based web application.

---

## ✅ Key Features

* Predicts six major water pollutants using Random Forest Regression  
* Uses `MultiOutputRegressor` to handle multiple pollutant targets simultaneously  
* Includes an interactive web app (`app.py`) for real-time predictions  
* Generates visualizations: correlation heatmap and actual vs. predicted plots  
* Modular code with reusable prediction function: `predict_pollutants(station_id, year)`

---

## 📈 Predicted Water Quality Parameters

* Oxygen (O₂)  
* Nitrate (NO₃)  
* Nitrite (NO₂)  
* Sulphate (SO₄)  
* Phosphate (PO₄)  
* Chloride (CL)

---

## 💻 Streamlit Web App

The project includes a web app that allows users to input a **station ID** and **year**, and receive predicted pollutant levels in both tabular and visual form.

### ▶️ To Run the App:

```bash
streamlit run app.py
