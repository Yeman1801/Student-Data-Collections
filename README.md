## ✅ Requirements

## 🔧 1. Python Installation
✅ Latest Stable Version (as of July 2025): Python 3.12

# 📥 Download: https://www.python.org/downloads/

After installation:

### python --version
# Output should be something like: Python 3.12.x
✅ Tkinter is still included by default in Python 3.12 (no need to install it).

## 💻 2. PyCharm Installation
✅ Latest Version (as of July 2025): PyCharm 2024.1 or 2024.2

📥 Download: https://www.jetbrains.com/pycharm/download/

You can use either the Community (Free) or Professional edition.

## 📦 3. Updated Library Installation
In PyCharm Terminal or command line, run:

pip install mysql-connector-python
pip install pillow
pip install openpyxl
pip install xlrd
All these libraries support Python 3.12 and work well in PyCharm 2024.x.

## 🗃️ Recommended Project Folder Structure (2025 Standard)
Ensure your project looks like this in PyCharm:

StudentRegistrationSystem/
│
├── login.py
├── newuser.py
├── student.py
├── Student_data.xlsx       ← (auto-created if missing)
├── Images/
│   ├── icon.png
│   ├── LOGIN.png
│   ├── register.png
│   ├── openeye.png
│   ├── close eye.png
│   ├── search.png
│   ├── Layer 4.png
│   ├── backbutton.png
│   └── upload photo.png
├── Student Images/         ← (auto-created after saving student photo)
🧠 Tip: Use lowercase folder and image names with correct spellings.

## ⚙️ MySQL Setup for 2025
### 1. ✅ Latest Version: MySQL 8.3
📥 Download: https://dev.mysql.com/downloads/mysql/

### 2. Setup MySQL User
Make sure you have a user:

## Username: your sql server name 

## Password: your sql password
(Or modify login.py and newuser.py to match your credentials.)

## 🚀 Run the App in PyCharm (2025 Way)
Open PyCharm

Create or Open a new project.

Put all your .py and Images/ files in the same project folder.

Right-click login.py and choose Run 'login'.

Use the interface to log in or create a new user.

