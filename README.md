📊 Student Performance Prediction System
🚀 Project Overview

This project is a Machine Learning-based web application that predicts a student's academic performance based on various socio-economic and academic factors. The system uses a trained ML model and provides predictions through a Flask-based web interface.

The goal is to demonstrate a complete end-to-end ML pipeline, including data preprocessing, model training, and deployment.

🧠 Problem Statement

Student performance is influenced by multiple factors such as:

Gender
Ethnicity
Parental education level
Lunch type
Test preparation course
Reading & Writing scores

This project aims to predict student performance (Math score) based on these inputs using machine learning techniques.

🏗️ Project Architecture

The project follows a modular and production-style architecture:

ML Project
│
├── artifacts/              # Saved models & datasets
├── notebook/               # EDA & Model training notebooks
├── src/
│   ├── components/         # Data ingestion, transformation, model training
│   ├── pipeline/           # Training & prediction pipeline
│   ├── exception/          # Custom exception handling
│   ├── logger/             # Logging functionality
│
├── templates/              # HTML files for UI
├── app.py                  # Flask application
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
⚙️ Features
✔️ End-to-end ML pipeline
✔️ Data preprocessing using pipelines
✔️ Model training and evaluation
✔️ Model persistence (Pickle files)
✔️ Web interface using Flask
✔️ Real-time predictions
🔍 Workflow
Data Ingestion
Load dataset and split into train/test
Data Transformation
Handle categorical & numerical features
Apply scaling and encoding
Model Training
Train multiple models
Select best-performing model
Model Saving
Save model and preprocessor (.pkl files)
Prediction Pipeline
Take user input from UI
Transform input data
Generate predictions
Web Deployment
Flask app serves predictions via UI
🧪 Technologies Used
Python
Pandas, NumPy
Scikit-learn
CatBoost (for model training)
Flask (Web framework)
HTML/CSS (Frontend)
📈 Input Features
Gender
Race/Ethnicity
Parental Level of Education
Lunch Type
Test Preparation Course
Reading Score
Writing Score
📤 Output
Predicted Math Score
