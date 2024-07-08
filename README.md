# Task-Manager
## Todo List Application

## Overview
This Todo List Application is a web-based task management system built using Flask, SQLAlchemy, and Jinja2. The application allows users to sign up, log in, and manage their personal todo lists. It supports basic CRUD (Create, Read, Update, Delete) operations on tasks and utilizes modern ARM (Authentication, Role-based Management) principles for user management.

## Features
- **User Authentication**: Secure user sign-up and sign-in functionality with password hashing.
- **Role-based Management (ARM)**: Each user can manage their own tasks without interference from other users.
- **CRUD Operations**: Create, Read, Update, and Delete tasks.

## Technologies Used
- **Flask**: A micro web framework written in Python.
- **SQLAlchemy**: SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **Jinja2**: A templating engine for Python.
- **Werkzeug**: A comprehensive WSGI web application library.
- **HTML/CSS**: For the frontend.

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/Daman2461/Task-Manager.git
    cd Task-Manager
    ```

2. **Create and activate a virtual environment**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the database**
    ```bash
    flask db init
    flask db migrate -m "Initial migration."
    flask db upgrade
    ```

5. **Run the application**
    ```bash
    flask run
    ```

## Usage

### User Sign Up
- Navigate to `/signup/` to create a new user account.
- Provide a unique username and password.

### User Sign In
- Navigate to `/signin/` to log in to your account.
- Enter your username and password.

### Managing Tasks
- Once logged in, you will be redirected to your home page where you can:
  - **Create** new tasks.
  - **Read** and view your list of tasks.
  - **Update** existing tasks.
  - **Delete** tasks that are no longer needed.

### User Sign Out
- Click on the sign-out link to log out of your account and end your session.



