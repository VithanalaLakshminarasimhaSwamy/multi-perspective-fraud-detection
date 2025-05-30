
# 🛡️ Multi-Perspective Fraud Detection for E-Commerce Transactions

A web-based machine learning project to detect fraudulent transactions in multi-participant e-commerce systems by analyzing behavior using a combination of process mining and machine learning (SVM, etc.).

---

## 🚀 Features

- 📊 Analyze user behavior from multiple perspectives (time, resource, control flow)
- ✅ Predict whether a transaction is fraudulent
- 🔐 Role-based login for Remote Users and Service Providers
- 📈 Visualize model accuracy using graphs (bar, pie, line)
- 🧠 SVM-based classification integrated with Django backend
- 📂 Upload and process datasets from the admin interface

---

## 🏗️ Tech Stack

| Layer         | Technology                          |
|---------------|--------------------------------------|
| Frontend      | HTML, CSS, JavaScript                |
| Backend       | Python, Django                       |
| Database      | MySQL (via WAMP/XAMPP)               |
| ML Algorithms | SVM, Decision Tree, Logistic Regression, Naive Bayes, Random Forest |
| Visualization | Matplotlib                           |
| Deployment    | Git + GitHub                         |

---

## 🧰 Requirements

Install dependencies using either of the two methods below:

👉 Option 1: Using requirements.txt

```bash
pip install -r requirements.txt
````

👉 Option 2: Manually install each package

```bash
pip install django mysqlclient numpy pandas scikit-learn matplotlib joblib
```

---

## 🛠️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/multi-perspective-fraud-detection.git
cd multi-perspective-fraud-detection
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate       # On Windows
# source venv/bin/activate  # On Mac/Linux
```

3. Install dependencies (see Requirements section above)

4. Set up the MySQL database:

* Open XAMPP or MySQL Workbench
* Create a database named fraud\_detection
* Update database config inside:
  a\_multiperspective\_fraud\_detection/settings.py

Example:

```python
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
```

5. Apply Django migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

6. Run the server:

```bash
python manage.py runserver
```

7. Open your browser and visit:

[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

🚀 Done! The app should now be running locally.

---

## 📸 Screenshots Overview

| Screenshot                 | Description                                           |
|----------------------------|-------------------------------------------------------|
| Home Page                  | Entry screen of the web application                  |
| Registration Page          | Allows users to register with details                |
| Remote User Login          | User login screen for accessing prediction features  |
| Remote User Details Table  | Displays all remote users and their metadata         |
| Accuracy Line Graph        | Line chart showing accuracy of ML models             |
| Accuracy Bar Chart         | Bar chart comparison of ML models by performance     |
| Accuracy Pie Chart         | Pie chart showing proportional accuracy of algorithms|



## 🖼️ Screenshots

### 🏠 Home Page
![Home Page](screenshots/HomePage.jpg)

### 📝 Registration Page
![Registration Page](screenshots/RegistrationPage.jpg)

### 🔐 Remote User Login
![Remote User Login](screenshots/RemoteUserLogin.jpg)

### 📈 Accuracy Comparison – Line Graph
![Line Graph](screenshots/LineGraph.jpg)

### 🥧 Accuracy Comparison – Pie Chart
![Pie Chart](screenshots/PieChart.jpg)

### 👥 Remote User Details Table  
![Details of Remote Users](screenshots/DetailsofRemoteUsers.jpg)

### 📈 Accuracy Comparison – Line Graph  
![Line Graph](screenshots/LineGraph.jpg)

### 📊 Accuracy Comparison – Bar Chart  
![Bar Chart](screenshots/BarChart.jpg)



## 👨‍💻 Developed By

* V. Lakshminarasimha Swamy
* G. Jagan
* K. Daniel Babu
* G. Shashi Kumar

> Under the guidance of 
> Dept. of CSE-AIML, CMR Engineering College

---

## 📜 License

This project is intended for academic learning and educational submission.
Not intended for commercial use.

````

