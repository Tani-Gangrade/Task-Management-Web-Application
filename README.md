# Task Management Web Application
 It's a simple task management web application built using Flask and SQLAlchemy. It allows users to create, update, and delete tasks.

---

## Features
- Add new tasks with a description.
- View a list of all tasks.
- Update existing tasks.
- Delete tasks.

## Prerequisites
- Python 3.12 or higher
- Flask
- Flask-SQLAlchemy

## Usage
- Add Task: Enter a task description in the input field and click "Add Task".
- Update Task: Click the "Update" link next to a task, modify the description, and submit.
- Delete Task: Click the "Delete" link next to a task to remove it.

## File Descriptions
- app.py: Contains the Flask application logic, routes, and database model.
- templates/: HTML templates for rendering the web pages.
- static/css/main.css: Stylesheet for the application.
- env/: Virtual environment for managing dependencies.

## Database
The application uses SQLite as the database. The database file is named test.db and is automatically created in the project directory.
