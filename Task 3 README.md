# Flask Notes Application

## Overview

The **Flask Notes Application** is a simple full-stack web application developed using **Python**, **Flask**, and **SQLite**. The application allows users to register, log in securely, create personal notes, view saved notes, and delete notes. It demonstrates the implementation of user authentication, session handling, database management, and CRUD operations using the Flask framework.

This project was developed as part of a **Python Development Internship** to demonstrate the fundamentals of full-stack web development.

---

## Features

- User Registration
- Secure User Login
- Password Hashing
- Session Management
- Add Notes
- View Notes
- Delete Notes
- Logout
- SQLite Database Integration
- Simple and Responsive User Interface

---

## Technologies Used

### Programming Language
- Python

### Backend Framework
- Flask

### Database
- SQLite

### Frontend
- HTML
- CSS

### Python Libraries
- Flask
- sqlite3
- werkzeug.security
- threading

---

## Project Structure

```
Flask_Notes_App/
│
├── app.py
├── notes.db
├── README.md
├── requirements.txt
└── screenshots/
```

---

## System Workflow

1. Initialize the SQLite database.
2. Register a new user account.
3. Store user credentials securely.
4. Log in using registered credentials.
5. Create a user session.
6. Display the user dashboard.
7. Add new notes.
8. Store notes in the SQLite database.
9. View all saved notes.
10. Delete unwanted notes.
11. Logout and end the session.

---

## Database

The project uses **SQLite** and contains two tables.

### Users Table

| Column | Description |
|--------|-------------|
| id | User ID |
| username | Username |
| password | Encrypted Password |

### Notes Table

| Column | Description |
|--------|-------------|
| id | Note ID |
| username | Username |
| note | User Note |

---

## How to Run

### 1. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 2. Run the Application

```bash
python app.py
```

### 3. Open in Browser

```
http://127.0.0.1:5000
```

---

## Output

The application provides the following pages:

- User Registration Page
- User Login Page
- Dashboard
- Add Notes
- View Notes
- Delete Notes
- Logout

---

## Applications

- Personal Note Management
- Student Notes
- Task Recording
- Learning Flask Framework
- CRUD Application Development
- Authentication System Demonstration

---

## Advantages

- Lightweight web application
- Secure password hashing
- Session-based authentication
- Simple and responsive interface
- Easy to understand
- Beginner-friendly Flask project
- Uses SQLite for efficient data storage

---

## Limitations

- Designed for local execution
- Supports only basic note management
- No note editing functionality
- No search feature
- No cloud database integration

---

## Future Enhancements

- Edit existing notes
- Search notes
- Note categories
- Dark mode
- User profile management
- Password reset
- Email verification
- File attachments
- Cloud database support
- Deploy using Render or PythonAnywhere

---

## Note

This project was developed in **Google Colab** for coding purposes. Since Flask applications are designed to run as local web servers, the application should be executed in a local Python environment (such as VS Code, PyCharm, or IDLE) to access the complete web interface.

---

## Conclusion

The Flask Notes Application demonstrates the development of a complete full-stack web application using Python, Flask, SQLite, HTML, and CSS. It successfully implements user authentication, session management, database operations, and CRUD functionality while providing a clean and user-friendly interface. This project serves as a strong beginner-level example of Flask-based web development.

---

## Author

**M. Ayshwarya**

**Aeronautical Engineering Graduate**

**Python Development Internship Project**
