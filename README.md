# 🧠 Mansik Santulan Score

### ML-Based Student Mental Wellness Score Prediction

DataSet Link : https://www.kaggle.com/datasets/shivasingh4945/student-social-media-and-mental-health-impact

🔗 **Live Demo:** https://mansik-santulan-score-1-k4s9.onrender.com

## 📌 About the Project

Mansik Santulan Score is an end-to-end Machine Learning project that predicts a student's mental wellness score based on their:

* Social media usage
* Daily phone unlocks
* Study hours
* Sleep duration
* Physical activity
* Stress level
* Academic and demographic information

The project uses supervised learning regression models and is deployed as a live web application.

> ⚠️ This project is for educational purposes only and is not a medical or clinical diagnostic tool.

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* FastAPI
* Joblib
* Render

## 🤖 Machine Learning

Models evaluated:

* Linear Regression
* Random Forest Regressor
* Tuned Random Forest Regressor

### Final Model

**Random Forest Regressor**

* **R² Score:** 0.878
* **MAE:** 0.347
* **RMSE:** 0.464

The complete preprocessing and model pipeline was saved using `joblib` and integrated with the FastAPI backend.

## 🔄 ML Workflow

```text
Data
  ↓
Data Cleaning
  ↓
EDA
  ↓
Feature Engineering
  ↓
Preprocessing
  ↓
Model Training
  ↓
Evaluation
  ↓
FastAPI Integration
  ↓
Deployment
```

## 🚀 Project Structure

```text
├── ML_Project.ipynb
├── main.py
├── Mental_Health_Model.pkl
├── requirements.txt
└── frontend/
```

## 👩‍💻 Author

**Mansi Chaudhary**

B.Tech — Artificial Intelligence & Machine Learning

⭐ If you found this project interesting, consider starring the repository!
