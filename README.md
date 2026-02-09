# Hospital Management System 

## Overview
This is a simple web-based Hospital Management System built using **Python** and **Flask**. The project allows you to manage hospital departments, staff, and patients through an interactive dashboard.  

It demonstrates the use of **Object-Oriented Programming (OOP)** with classes such as `Hospital`, `Department`, `Patient`, and `Staff`, along with a web interface for managing them.

---

## Features
- **Admin Login:**  
  - Username: `admin`  
  - Password: `123`

- **Manage Departments:**  
  - Add new departments dynamically.  

- **Manage Patients:**  
  - Add patients to specific departments.  
  - View patient records.

- **Manage Staff:**  
  - Add staff members to departments.  
  - View staff information.

- **Interactive Dashboard:**  
  - All operations are done from a single dashboard.  
  - Styled with CSS, including background images and centered forms.  

---

## Project Structure

    Hospital-Management/
    │
    ├─ app.py
    ├─ Hospital.py
    ├─ Department.py
    ├─ Patient.py
    ├─ Staff.py
    ├─ Person.py
    ├─ Main.py
    ├─ templates/
    │ ├─ login.html
    │ └─ dashboard.html
    ├─ static/
    │ ├─ style.css
    │ └─ hospital.jpg
    └─ README.md


---

## Technologies Used
- **Python 3**
- **Flask** (Web framework)
- **HTML / CSS** (Frontend)
- **OOP Principles** (Classes & methods)

---

## How to Run

1. **Clone the repository:**
   ```bash
   git clone <repo_url>
   cd Hospital-Management
   
2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   venv\Scripts\activate   # Windows
   source venv/bin/activate # Linux/Mac
   
3. **Install dependencies:**
   ```bash
   pip install flask

4. **Run the application:**
   ```bash
   python App.py

5. **Login with:**  
  - Username: admin  
  - Password: 123 



