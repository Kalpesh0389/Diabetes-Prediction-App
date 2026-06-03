<div align="center">

# 🩺 Diabetes Prediction System

![Status](https://img.shields.io/badge/Status-Active-success)
![Tech](https://img.shields.io/badge/Machine%20Learning-Flask-blue)
![License](https://img.shields.io/badge/License-MIT-orange)

<h3 align="center">
🌐 Live Demo:
<a href="https://kalpesh123.pythonanywhere.com/">Visit Website</a>
&nbsp;|&nbsp;
📂 GitHub:
<a href="https://github.com/Kalpesh0389">View Repository</a>
</h3>

</div>

---

## 📌 About DiabetaML

**DiabetaML** is a web-based Machine Learning application that predicts whether a person is **Diabetic or Non-Diabetic** based on key medical input parameters — instantly and with no medical expertise required.

Built using a **Logistic Regression** model trained on the Pima Indians Diabetes dataset, the application is deployed as a clean, accessible Flask web app on PythonAnywhere. DiabetaML focuses on **real-time prediction**, **clinical input accuracy**, and **simplicity of use**, making health screening more accessible to everyone.

> ⚠️ *This tool is for educational purposes only. Always consult a healthcare professional for medical diagnoses.*

---

## ✨ Key Highlights

* 🤖 Logistic Regression model trained on the Pima Indians Diabetes dataset
* ⚡ Real-time Diabetic / Non-Diabetic prediction from medical inputs
* 💾 Trained model serialized and served via Pickle
* 🌐 Live deployment on PythonAnywhere
* 🧹 Clean Flask web UI with no setup required for end users
* 📊 7 clinically relevant input features for accurate prediction

---

## 🚀 Features

### 👤 User Features
* Enter medical parameters through a simple, clean web form
* Get instant Diabetic / Non-Diabetic prediction results
* No account or login required — accessible to anyone
* Responsive UI built with HTML5 & CSS3

### 🧠 ML Engine Features
* Logistic Regression model trained with Scikit-learn
* Pima Indians Diabetes dataset as training source
* `Pregnancies` feature dropped for broader generalizability
* Model saved with Pickle for fast, reliable inference
* 7-feature input pipeline: Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age

### 🛠️ Backend Features
* Flask REST backend handling form submissions & predictions
* Pickle-based model loading for lightweight deployment
* Minimal dependency footprint for easy hosting
* Deployed and live on PythonAnywhere

---

## 🏗️ Tech Stack

| Layer       | Technologies                              |
| ----------- | ----------------------------------------- |
| Frontend    | HTML5, CSS3                               |
| Backend     | Python, Flask                             |
| ML Library  | Scikit-learn (Logistic Regression)        |
| Data        | Pandas, Pima Indians Diabetes Dataset     |
| Serialization | Pickle                                  |
| Deployment  | PythonAnywhere                            |

---

## 🧠 Machine Learning Details

| Component        | Details                          |
| ---------------- | -------------------------------- |
| Algorithm        | Logistic Regression              |
| Library          | Scikit-learn                     |
| Dataset          | Pima Indians Diabetes Dataset    |
| Target Variable  | Outcome (Diabetic / Non-Diabetic)|
| Dropped Feature  | Pregnancies                      |

### 🔢 Input Features Used
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

---

## 📁 Project Structure

```
diabetes-prediction/
│
├── app.py                  # Flask application & prediction route
├── train_model.py          # Model training script
├── diab.pkl                # Serialized Logistic Regression model
├── diabetes.csv            # Pima Indians Diabetes dataset
├── requirements.txt        # Python dependencies
├── README.md
│
└── templates/
    └── home.html           # Frontend form & result UI
```

---

## ⚙️ Installation & Setup

### Prerequisites
* Python 3.x
* pip
* Git

### Clone Repository
```bash
git clone https://github.com/Kalpesh0389/diabetes-prediction.git
cd diabetes-prediction
```

### Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
python app.py
```

### Open in Browser
Navigate to: `http://localhost:5000`

---

## 🌐 Environment & Deployment

The app is deployed on **PythonAnywhere** with no additional environment variables required.

For local development, ensure all dependencies in `requirements.txt` are installed and the `diab.pkl` model file is present in the project root before running `app.py`.

---

## 🔮 Future Enhancements

* 📈 Feature scaling for improved model performance
* 🧪 Advanced algorithms (Random Forest, XGBoost) for higher accuracy
* 📊 Show prediction confidence / probability score
* 🎨 Bootstrap or Tailwind UI redesign
* ☁️ Cloud deployment on AWS or Render
* 📧 Email report generation for prediction results

---

## 👨‍💻 Author

**Kalpesh Remje**

Full Stack & ML Developer

📧 Email: [remjekalpesh486@gmail.com](mailto:remjekalpesh486@gmail.com)

🔗 GitHub: [https://github.com/Kalpesh0389](https://github.com/Kalpesh0389)

---

## 📜 License

This project is licensed under the **MIT License** — see the LICENSE file for details.

---

<div align="center">
⭐ <em>If you like this project, don't forget to star the repository!</em> ⭐
</div>
