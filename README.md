🩺 Diabetes Prediction System
Flask + Machine Learning Web Application

<p align="center"> <img src="https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-blue" alt="Machine Learning"> <img src="https://img.shields.io/badge/Web%20Framework-Flask-green" alt="Flask"> <img src="https://img.shields.io/badge/Deployment-PythonAnywhere-orange" alt="PythonAnywhere"> </p><h3 align="center">🌐 Live Demo: <a href="https://kalpesh123.pythonanywhere.com/">https://kalpesh123.pythonanywhere.com/</a></h3>
📌 Project Overview
The Diabetes Prediction System is a web-based Machine Learning application that predicts whether a person is Diabetic or Non-Diabetic based on medical input parameters.

The application uses a Logistic Regression model trained on the Pima Indians Diabetes dataset and is deployed using Flask on PythonAnywhere.

🚀 Features
<p align="left"> <strong>✅ Machine Learning model</strong> using Logistic Regression<br> <strong>✅ Trained model</strong> saved with Pickle<br> <strong>✅ Flask web application</strong> with a clean UI<br> <strong>✅ Real-time prediction results</strong><br> <strong>✅ Deployed live</strong> on PythonAnywhere </p>
🧠 Machine Learning Details
Component	Details
Algorithm	<img src="https://img.shields.io/badge/Logistic_Regression-FF6B6B" alt="Logistic Regression">
Library	<img src="https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white" alt="Scikit-learn">
Target Variable	Outcome
Dropped Feature	Pregnancies
🔢 Input Features Used:
• Glucose
• Blood Pressure
• Skin Thickness
• Insulin
• BMI
• Diabetes Pedigree Function
• Age

🛠️ Technologies Used
<div align="center"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn"> <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"> <img src="https://img.shields.io/badge/Pickle-Data_Serialization-lightgrey?style=for-the-badge" alt="Pickle"> <img src="https://img.shields.io/badge/PythonAnywhere-Deployment-yellow?style=for-the-badge" alt="PythonAnywhere"> </div>
📁 Project Structure
Project Root
diabetes-prediction/

├── app.py              
├── train_model.py      
├── diab.pkl            
├── diabetes.csv       
├── requirements.txt    
├── README.md           
├── templates/          
│   └── home.html

└── static/            

⚙️ Installation & Setup
Clone the repository

bash
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
Create virtual environment

bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies

bash
pip install -r requirements.txt
Run the Flask application

bash
python app.py
Open in browser
Navigate to: http://localhost:5000

📌 Future Enhancements
<p align="left"> 🔹 <strong>Feature scaling</strong> for better model performance<br> 🔹 <strong>Improve model accuracy</strong> with advanced algorithms<br> 🔹 <strong>Show prediction probability</strong><br> 🔹 <strong>Add Bootstrap UI</strong> for better design<br> 🔹 <strong>Deploy on cloud platforms</strong> like AWS / Render </p>

👨‍💻 Author - Kalpesh Remje

📧 Contact: remjekalpesh486@gmail.com

🔗 GitHub: https://github.com/Kalpesh0389

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

⚠️ Disclaimer: This tool is for educational purposes only. Always consult healthcare professionals for medical diagnoses.

<div align="center"> <p><strong>Made with ❤️ and Python</strong></p> <img src="https://img.shields.io/badge/Health-Tech-4CAF50" alt="Health Tech"> <img src="https://img.shields.io/badge/AI-For_Good-9C27B0" alt="AI for Good"> </div>
