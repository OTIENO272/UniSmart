
# 🎓 UniSmart –Simple University Student Management System

A professional desktop application developed using **PyQt5** and **MySQL** for managing university student records.

---

## 📌 Project Overview

UniSmart is a CRUD-based system that allows users to:

- Add new student records  
- Update existing records  
- Delete records  
- Search students by Registration Number  
- Navigate records (Next / Previous)  
- Reset form inputs  
- View all data in a structured table  

The system is designed following **software engineering best practices**, including modular design and clean architecture.

---

## 🧱 System Architecture

The project follows a structured layered design:
UI Layer (PyQt5)
↓
Controller Layer (Logic)
↓
Database Layer (MySQL)


---

## 🖥️ User Interface Features

- Clean and modern UI styling  
- Input validation support  
- Table view for all records  
- Navigation buttons (Next / Previous)  
- Clear feedback using message boxes  

---

## 🗄️ Database Design

### Database Name:University

### Table: Students

```sql
CREATE TABLE Students (
    RegistrationNumber VARCHAR(20) PRIMARY KEY,
    SecondName VARCHAR(50),
    Surname VARCHAR(50),
    Course VARCHAR(50),
    County VARCHAR(50),
    Gender VARCHAR(10),
    Department VARCHAR(50),
    School VARCHAR(50)
);
```
---
### 🛠️ Technologies Used
```

-Python 3
-PyQt5 (GUI)
-MySQL (Database)
-mysql-connector-python

```


### 📦 Installation & Setup
1. Clone the repository
   ```
   git clone https://github.com/OTIENO272/UniSmart.git
   cd UniSmart


### 2. Install dependencies
```
pip install -r requirements.txt
```
### 3. Setup MySQL Database

### Create the database and table: 
```
CREATE DATABASE University;
USE University;

CREATE TABLE Students (
    RegistrationNumber VARCHAR(20) PRIMARY KEY,
    SecondName VARCHAR(50),
    Surname VARCHAR(50),
    Course VARCHAR(50),
    County VARCHAR(50),
    Gender VARCHAR(10),
    Department VARCHAR(50),
    School VARCHAR(50)
);
```

### 4. Run the application
### File Conversion 
use the jupyter nbconvert --to script your_notebook.ipynb command in your terminal
1.Open your command prompt or terminal.
2.Navigate to the directory containing your file.
3.Run
'''
jupyter nbconvert --to script your_notebook.ipynb

Name the file properly
```
python main.py 
```
### 📁 Project Structure
```
UniSmart/
│
├── app/
│   ├── main.py
│   ├── ui/
│   ├── database/
│   └── controllers/
│
├── assets/
├── requirements.txt
├── README.md
└── .gitignore
```
### 👨‍💻 Developer
VichDev308

