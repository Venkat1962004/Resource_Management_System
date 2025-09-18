# Academic Resource Management System

## 📌 Overview  
A web application for managing academic resources (past exam papers), built with role-based access (Admin / Teacher / Student). Enables uploading, viewing, and managing documents in a secure, structured way.

---

## 🚀 Features  
- Role-Based Access: Admins can upload resources; Teachers and Students can view and download based on permissions.  
- Secure File Storage: Structured server-side directory for resource files; metadata (title, uploader, timestamp) stored in a PostgreSQL database.  
- User-Friendly Interface: Clean UI for navigating, searching, and filtering past papers.

---

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Web Framework:** Flask  
- **Frontend:** HTML5, CSS3 (optionally Bootstrap)  
- **Database:** PostgreSQL  
- **Tools & Other:** Git & GitHub, RESTful APIs, File I/O operations in Python

---

## 📂 Project Structure  
├── app.py # Main application logic & routing

├── static/ # CSS, JS, images

├── templates/ # HTML templates

├── uploads/ # Folder where resources (PDFs etc.) are stored

├── database_setup.py # DB schema setup and migrations

├── models.py # ORM or DB models

├── requirements.txt # Dependencies list

└── README.md # Project documentation


---

## ⚡ Installation & Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Venkat1962004/Resource_Management_System.git
   cd Resource_Management_System
Set up a virtual environment (recommended):

python3 -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt
Configure database:

### 4. Configure the Database  
- Install **PostgreSQL** (if not already installed).  
- Create a new database (e.g., `resource_db`).  
- Update the database connection string inside **`app.py`** or **`config.py`**.  


Run the app:
python app.py


🎯 Use Case

This tool is useful for educational institutions, teachers, and students to archive and organize past exam papers and other academic resource materials, simplifying access and reducing redundancy.

📖 Future Enhancements
## 📖 Future Enhancements  
- Add **search/filter** functionality (by subject, date, or teacher).  
- Enable **role-based dashboards** with usage statistics.  
- Implement **user authentication** (login/register) and permission management.  
- Deploy the system on **cloud platforms** for scalability.  

