## 📝 Flask Notes App

A simple **note-taking web application** built with Python **Flask** and **SQLite**.  
This project was created as a **practice project** to learn Flask basics before developing my major project *CivicConnect*.  

---

## Features
- User authentication (Register/Login/Logout)
- Add new notes
- Edit and delete existing notes
- Store notes securely in SQLite database
- Clean and simple UI with Bootstrap

---

## 🛠 Tech Stack
- **Backend**: Python (Flask)  
- **Frontend**: HTML, CSS, Bootstrap  
- **Database**: SQLite  

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/nashwa-b/flask-notes-app.git
   cd flask-notes-app
   
2. **Create virtual environment & install dependencies**
    python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
pip install -r requirements.txt

3. **Run the Flask app**
   python -m website.main

4. **Open in browser**
   http://127.0.0.1:5000

📂 **Project Structure**

flask-notes-app/
│── website/
│   ├── __init__.py        # App factory
│   ├── auth.py            # Authentication routes
│   ├── main.py            # Main app routes
│   ├── models.py          # Database models
│   ├── views.py           # Extra routes
│   ├── static/            # CSS/JS files
│   │   ├── style.css
│   │   └── index.js
│   └── templates/         # HTML templates
│       ├── base.html
│       ├── home.html
│       ├── login.html
│       └── sign_up.html
│
│── instance/              # Database storage
│── requirements.txt       # Dependencies
│── README.md              # Documentation
│── LICENSE                # MIT License
│── .gitignore             # Ignored files


**Learning Goals**

• Learn Flask app structure with Blueprints
• Understand CRUD operations with SQLite
• Practice user authentication in Flask
• Get hands-on experience before building CivicConnect

## 📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this project with proper attribution.

See the LICENSE
 file for details.

 
---


