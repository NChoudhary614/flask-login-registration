🔐 Flask Login & Registration System
[![Python Version](https://img.shields.io/badge(https://www.python.org/download
[![Flask Version](https://img.shields.io/badge(https://palletsprojects.com
[![License](https://img.shields.io/badge

Overview
This project is a simple and secure user login and registration system built with Python, Flask, and MySQL.
It features:

User registration with input validation

User login with session management

Dynamic HTML templates using Jinja2

MySQL integration for persistent user data

Basic CSS styling for clean UI

Ready for local development and easy deployment

Demo
To run locally, clone this repo and follow setup instructions below.
The app runs on http://127.0.0.1:5000/.

Folder Structure
text
My_Project_Folder/
├── app.py                 # Main Flask app
├── requirements.txt       # Python packages
├── templates/             # HTML templates
│   ├── register.html
│   ├── login.html
│   └── index.html
├── static/                # CSS, JS, images
│   ├── style.css
│   └── js/main.js
└── .venv/                 # Virtual environment (optional)
Installation & Setup
Clone the repo

bash
git clone <your-repo-url>
cd <your-repo-folder>
Create and activate virtual environment

bash
python -m venv .venv
# On Windows
.\.venv\Scripts\activate
# On macOS/Linux
source .venv/bin/activate
Install Dependencies

bash
pip install -r requirements.txt
Configure MySQL Database

Install MySQL server locally.

Create database and accounts table as specified.

Update database config in app.py.

Run the Flask App

bash
python app.py
Open your browser at http://127.0.0.1:5000/register to use the app.

Technologies Used
Technology	Purpose
Python 3.11	Backend programming
Flask	Web framework
MySQL	Database
HTML/CSS/JS	Frontend UI & interactions
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Contributions, issues, and feature requests are welcome!
Feel free to check issues or submit pull requests.
