🌊 Final Project – Water Quality Prediction (Streamlit-Enabled Version)
This final version of the Water Quality Prediction project presents a complete end-to-end machine learning solution — from data preprocessing and multi-output regression to model evaluation and deployment via an interactive Streamlit app. The project was developed during the AICTE Virtual Internship, conducted by Edunet Foundation and sponsored by Shell in June 2025.

🎯 Objective
To create a scalable and user-friendly predictive model that estimates key water pollutant levels based on station ID and year, and deliver real-time results through a Streamlit-powered web interface.

✅ Key Features
Predicts six major water pollutants using Random Forest Regression

Leverages MultiOutputRegressor to forecast multiple pollutant levels simultaneously

Provides an intuitive Streamlit web app (app.py) for on-demand predictions

Includes meaningful visualizations: correlation heatmap, actual vs. predicted plots

Offers a reusable prediction function: predict_pollutants(station_id, year)

📈 Predicted Pollutants
Oxygen (O₂)

Nitrate (NO₃)

Nitrite (NO₂)

Sulphate (SO₄)

Phosphate (PO₄)

Chloride (CL)

💻 Web Application
The Streamlit interface enables users to input a monitoring station ID and year, then instantly receive predicted pollutant concentrations in both tabular and graphical formats.

▶️ How to Run
bash
Copy
Edit
streamlit run app.py
📁 Project Structure
Water_Quality_Prediction.ipynb – Final notebook with complete ML workflow

app.py – Streamlit app script

pollution_model.pkl – Trained ML model

model_columns.pkl – Encoded column mappings

Water_Quality_Prediction_Dataset.csv – Cleaned and preprocessed dataset

requirements.txt – List of required packages

README.md – Documentation for project overview and setup

🛠️ Tools & Technologies
Python 3.12

Pandas, NumPy – Data preprocessing

Scikit-learn – Machine learning framework

Matplotlib, Seaborn – Data visualization

Joblib – Model persistence

Streamlit – Web application framework

Jupyter Notebook – Development environment

📊 Model Evaluation Metrics
R² Score – Measures explained variance

Mean Squared Error (MSE) – Quantifies prediction error

📅 Internship Overview
Internship: AICTE Virtual Internship

Organizer: Edunet Foundation

Sponsor: Shell

Timeline: June 2025

Phase: Week 3 – Final Project

Domain: Artificial Intelligence for Environmental Monitoring

