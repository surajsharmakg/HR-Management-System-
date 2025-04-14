HR Management System
A comprehensive and modular HR Management System designed to streamline human resources operations such as employee management, departmental structuring, position tracking, and hiring pipeline visualization.

🛠️ Features
Relational Database Design
Designed and implemented a robust relational database schema to efficiently manage:

Employees

Departments

Positions

Hiring Candidates

Responsive Web Interface
Built a user-friendly web UI with:

A central dashboard displaying real-time HR metrics

Pages to view and manage employee data

Flask Backend
Developed a complete backend using the Flask framework:

RESTful routes for CRUD operations

Separation of concerns: database interaction, application logic, and presentation

Data Visualization
Integrated visualization tools to track:

Key HR metrics

Candidate progress through the hiring pipeline

Optimized Storage
Utilized SQLite for lightweight and efficient data storage with performance-tuned SQL queries.

Scalable Architecture
Built with a modular code structure to facilitate future enhancements and maintenance.

🚀 Technologies Used
Backend: Python, Flask

Frontend: HTML, CSS

Database: SQLite (designed for portability; can be adapted to MySQL)

Others: SQL, Jinja2 templates

📂 Folder Structure (Optional if you want to include)
pgsql
Copy
Edit
├── app/
│   ├── templates/
│   ├── static/
│   ├── routes/
│   ├── models/
│   └── __init__.py
├── database/
│   └── schema.sql
├── visualizations/
│   └── charts.py
├── run.py
└── README.md
