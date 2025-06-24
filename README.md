# 🔐 Secure Flask Login App

A secure and lightweight Flask application demonstrating login functionality using password hashing (bcrypt) and CSRF protection via Flask-WTF. Ideal for showcasing secure form handling and user authentication.

---

## 🛠️ Tech Stack

| Language | Framework | Hashing  | Security | IDE     |
| -------- | --------- | -------- | -------- | ------- |
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) | ![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask) | ![bcrypt](https://img.shields.io/badge/-bcrypt-003B57?style=flat) | ![CSRF](https://img.shields.io/badge/-CSRF%20Protection-orange?style=flat) | ![VSCode](https://img.shields.io/badge/-VSCode-007ACC?style=flat&logo=visualstudiocode) |

---

## 📂 Project Structure

```
secure_login_app/
├── app/
│   ├── __init__.py
│   ├── forms.py
│   ├── models.py
│   ├── routes.py
│   ├── static/
│   │   └── style.css
│   └── templates/
│       ├── base.html
│       ├── login.html
│       ├── register.html
│       └── dashboard.html
├── instance/
│   └── users.db
├── config.py
├── run.py
├── requirements.txt
└── README.md
```

---

## ✅ Features
🔐 Secure login and registration

🧂 Passwords hashed with bcrypt

🛡️ CSRF protection enabled

🧪 Session management with Flask

🧼 Clean & minimal form validation

🚫 Unauthorized route protection

---

## 🚀 Getting Started

1. Clone the repo:
git clone https://github.com/yourusername/secure-flask-login-app.git
cd secure-flask-login-app

2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install dependencies
pip install -r requirements.txt

4. Run the app
python run.py

Open your browser at: http://localhost:5000

---

## 🙌 Contribution
Contributions are welcome!  
Fork the project, create a new branch, push your changes, and open a pull request.

---

## 📜 License
This project is licensed under the MIT License.


