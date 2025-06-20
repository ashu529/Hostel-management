# Hostel Management System

# 🏨 Hostel Management System

A web-based Hostel Management System built using Python (Flask), HTML, CSS, and MySQL. This system allows administrators to manage hostel rooms, students, and allocations efficiently.

## 🚀 Features

- Add, edit, and delete rooms
- Register students and allocate rooms
- View current room allocations
- Responsive web interface using HTML and CSS
- Backend powered by Flask and MySQL

## 🛠️ Tech Stack

- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS
- **Database:** MySQL
- **Other:** Jinja2 templating

## 📁 Project Structure

hostel-management/
├── app.py # Main Flask app
├── db_config.py # Database connection settings
├── schema.sql # SQL script to create database tables
├── requirements.txt # Python dependencies
├── static/
│ ├── style.css # Styling for web pages
├── templates/
│ ├── add_room.html # HTML templates for various views
│ └── ...

bash
Copy
Edit

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/hostel-management.git
cd hostel-management
2. Install dependencies
It's recommended to use a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
3. Set up the MySQL database
Open MySQL client or phpMyAdmin.

Run the SQL script:


SOURCE schema.sql;
Update db_config.py with your MySQL credentials.
