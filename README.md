# 🏥 Patient Readmission Prediction System

## 📌 Project Overview  
Hospital readmissions within 30 days pose a significant challenge in healthcare, affecting both patient well-being and hospital costs. This project builds a **predictive machine learning model** that identifies patients at high risk of readmission using **Electronic Health Records (EHRs)**. The model is deployed in a **Django-based web application** to assist hospitals in proactive patient management.  

## 🔍 Problem Statement  
The goal is to **predict the likelihood of patient readmission** within 30 days using demographic data, medical history, hospital stay details, and treatment information. Hospitals can use this system to:  
✔️ Identify high-risk patients  
✔️ Recommend personalized interventions (e.g., follow-up care, medication adjustments)  
✔️ Optimize resource allocation to reduce readmission rates  

## 📂 Dataset  
The dataset used is from the **UCI Machine Learning Repository**, containing patient records from 130 hospitals (1999-2008).  
- **Demographics:** Age, gender, ethnicity  
- **Medical History:** Comorbidities (e.g., diabetes, hypertension)  
- **Hospital Stay:** Length of stay, previous admissions, ICU admission  
- **Treatment Data:** Medications, lab tests, discharge instructions  
- **Target Variable:** Readmission within 30 days (Yes/No)  

📌 **Dataset Link:** [UCI Diabetes Readmission Dataset](https://archive.ics.uci.edu/ml/datasets/diabetes+130-US+hospitals+for+years+1999-2008)  

## 🛠 Tech Stack  
- **Languages & Frameworks:** Python, Django, HTML/CSS  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow/PyTorch  
- **Database:** PostgreSQL/MySQL  
- **Deployment:** Docker, AWS/GCP  

## 🔎 Exploratory Data Analysis (EDA)  
✔️ Handling missing values & duplicates  
✔️ Distribution of readmission rates across different patient groups  
✔️ Feature importance analysis  
✔️ Correlation heatmaps & PCA  

## 🤖 Machine Learning Models  
The following models were trained and evaluated:  
✔️ **Logistic Regression** (Baseline Model)  
✔️ **Random Forest**  
✔️ **XGBoost & LightGBM**  
✔️ **Multi-Layer Perceptron (MLP) - Deep Learning Model**  

### 📊 Model Evaluation Metrics  
- **Accuracy:** Overall correctness of predictions  
- **Precision & Recall:** Important for imbalanced data  
- **F1-Score:** Balance between precision and recall  
- **ROC-AUC Score:** Measures model discrimination power  
- **Confusion Matrix:** Identifies misclassification patterns  

## 🌐 Web Application (Django)  
A **Django-based web app** was built for real-time patient readmission predictions.  

### Features:  
✔️ **User Input Form** – Enter patient details for prediction  
✔️ **Risk Score Visualization** – Display readmission probability  
✔️ **Downloadable Reports** – Generate patient risk assessment in PDF/CSV  
✔️ **REST API** – Secure API built with Django + FastAPI for integration  

## 🚀 Deployment  
✔ **Model Serialization** – Save trained models using `joblib` & `pickle`  
✔ **Backend API** – Django-based API for inference  
✔ **Frontend UI** – Bootstrap for a clean user interface  
✔ **Cloud Deployment** – Dockerized app hosted on AWS/GCP  

## 📌 How to Run Locally  
### 1️⃣ **Clone the Repository**  

- git clone https://github.com/your-username/patient-readmission-prediction.git
- cd patient-readmission-prediction

### 2️⃣ Create Virtual Environment & Install Dependencies

- python -m venv venv
- source venv/bin/activate  # (Mac/Linux) OR venv\Scripts\activate  # (Windows)
- pip install -r requirements.txt

### 3️⃣ Run Migrations & Start Django Server

- python manage.py makemigrations
- python manage.py migrate
- python manage.py runserver

### 4️⃣ Access Web App

- Open http://127.0.0.1:8000/ in your browser.

## 🎯 Future Improvements
- 🚀 Enhance model performance with more feature engineering
- 🚀 Integrate explainable AI (SHAP) for better interpretability
- 🚀 Extend API for real-time hospital data integration
- 🚀 Deploy as a SaaS product for healthcare providers

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit PRs.

## 📜 License
This project is licensed under the MIT License.

## 🔗 Connect with Me
- 📩 LinkedIn: Arsal Ali
- 📧 Email: arsalali687@gmail.com

- 💡 Let’s use AI to revolutionize healthcare! 🚀

#MachineLearning #HealthcareAI #Django #Python #DataScience #DeepLearning
