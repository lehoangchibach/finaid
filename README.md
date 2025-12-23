# finaid

# Project Setup Guide (Windows)

This guide walks you through setting up a local development environment using **Python 3.11** on Windows.

---

## 1. Prerequisites
Ensure you have **Python 3.11** installed. You can verify this by running:
```powershell
python --version
```

## 2. Activation
```powershell
.\.venv\Scripts\Activate.ps1
```

## 3. Install dependencies
```powershell
# Upgrade pip first
python -m pip install --upgrade pip

# Install dependencies
pip install -r requirements.txt
```

## 4. Run jupyter lab
```powershell
jupyter lab --port 8888
```

Once running, you can access the interface in your browser at:  
[`http://localhost:8888`](http://localhost:8888)

# How to use

The normal workflow usually consists of 3 scripts in this order:
* process_application
* create_student_appl_folder
* create_department folder

You can run each script by block by block approach.\
Please read through the comment in each individual script.\
You would often see this notation "./data", the "./" can be understand as a relative path from that script file location.\
So, "./data" means that the "data" folder at the same location as that script file.\