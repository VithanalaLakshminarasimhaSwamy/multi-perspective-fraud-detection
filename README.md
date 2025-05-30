# 🛡️ Multi-Perspective Fraud Detection for E-Commerce Transactions

A web-based machine learning project to detect fraudulent transactions in multi-participant e-commerce systems by analyzing behavior using a combination of **process mining** and **machine learning** (SVM, etc.).

---

## 🚀 Features

- 📊 Analyzes user behavior from multiple perspectives (time, resource, control flow)
- ✅ Predicts whether a transaction is fraudulent
- 🔐 Role-based login for Remote Users and Service Providers
- 📈 Visualizes model accuracy using graphs (bar, pie, line)
- 🧠 SVM-based classification integrated with Django backend
- 📂 Upload and process datasets from admin interface

---

## 🏗️ Tech Stack

| Layer            | Technology           |
|------------------|----------------------|
| Frontend         | HTML, CSS, JavaScript |
| Backend          | Python, Django       |
| Database         | MySQL (via WAMP)     |
| ML Algorithms    | SVM, Decision Tree, Logistic Regression, Naive Bayes, Random Forest |
| Visualization    | Matplotlib           |
| Deployment Ready | Git, GitHub          |

---

## 🧰 Requirements

Install required packages:

```bash
pip install -r requirements.txt
OR manually install:

bash
pip install django mysqlclient numpy pandas scikit-learn matplotlib
🛠️ How to Run
1. Clone the Repo
bash
Copy
Edit
git clone https://github.com/yourusername/multi-perspective-fraud-detection.git
cd multi-perspective-fraud-detection
2. Setup Virtual Environment
bash
Copy
Edit
python -m venv venv
venv\Scripts\activate       # Windows
# source venv/bin/activate  # Mac/Linux
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Setup MySQL Database
Create a DB named: fraud_detection

Update your settings.py with MySQL credentials

python
Copy
Edit
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'fraud_detection',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
5. Migrate and Run
bash
Copy
Edit
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
Visit: http://127.0.0.1:8000/

📸 Screenshots
Page	Description
Home	Landing page of the app
Remote Login	For user prediction access
Admin Login	Dataset upload & ML training
Graphs	Accuracy comparisons
Results	Transaction prediction outcome

(You can add actual images here using markdown later)

📄 Project Overview
Designed for final-year mini project submission

Based on real-world challenges in multi-user e-commerce fraud

Combines formal process modeling (Petri nets) with ML classification

Includes thorough testing, modular design, and database interaction

👨‍💻 Developed By
A. Sharath Chandra

M. Shreya

N. Hemanth Kumar

Sumit Guchhait

Under the guidance of Dr. Afshan Fathima, Dept. of CSE, CMR Institute of Technology

📜 License
This project is intended for academic learning and educational submission. Not intended for commercial use.
