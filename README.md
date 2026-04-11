# 🎯 Student Performance Prediction System

> *End-to-End Machine Learning Web Application*

A production-style Machine Learning project that predicts student academic performance (Math score) based on socio-economic and academic inputs. This project demonstrates a complete ML workflow — from data preprocessing and model training to deployment using a Flask web application.

---

## 🚀 Key Highlights

* ✔ End-to-End ML Pipeline (Data → Model → Deployment)
* ✔ Real-time Predictions via Web Interface
* ✔ Modular & Scalable Project Structure
* ✔ Industry-style Implementation using Pipelines
* ✔ Model Persistence using Pickle

---

## 🧠 Problem Statement

Student performance depends on multiple factors such as gender, parental education, lunch type, and test preparation. This system uses these features to predict a student's Math score using Machine Learning.

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn, CatBoost
* Flask (Backend)
* HTML, CSS (Frontend)

---

## 🏗️ Project Structure

```
ML Project
│
├── artifacts/          # Model & dataset files
├── notebook/           # EDA & training notebooks
├── src/
│   ├── components/     # Data ingestion, transformation, model training
│   ├── pipeline/       # Training & prediction pipelines
│   ├── exception/      # Custom exception handling
│   └── logger/         # Logging system
│
├── templates/          # HTML UI
├── app.py              # Flask app
├── requirements.txt
└── README.md
```

---

## 🔍 Workflow

1. Data Ingestion → Load & split dataset
2. Data Transformation → Encoding & scaling
3. Model Training → Train & select best model
4. Model Saving → Store model & preprocessor
5. Prediction Pipeline → Process user input
6. Deployment → Flask web interface

---

## 📊 Inputs

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score

---

## 📈 Output

🎯 Predicted Math Score

---

## ▶️ How to Run

```
git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt
python app.py
```

Open: http://localhost:5000

---

## ⚠️ Limitations

* No cloud deployment
* No REST API
* No model monitoring
* Basic UI

---

## 🔮 Future Improvements

* Deploy on AWS / Render
* Add FastAPI backend
* Improve UI/UX
* Add model evaluation dashboard

---

## 👨‍💻 Author

**Vasu**
B.Tech CSE | Aspiring Data Analyst / ML Engineer

---

> “A model without deployment is just an experiment.”
