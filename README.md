# Flask Login and Register System

This project is a simple Flask application that implements user authentication and registration functionality.

## Features

- User registration: Allows users to create a new account by providing a username, email, and password.
- User login: Allows registered users to log in to their account using their credentials.
- Session management: Uses Flask-Login to manage user sessions and authentication.
- Password hashing: Safely stores user passwords using secure hashing algorithms.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python (version 3.6 or higher)
- Flask
- Flask-Login
- Werkzeug (for password hashing)

## Installation

1. Clone this repository to your local machine:

```bash
   git clone <repository_url>
```

2. Navigate to the project directory:

```bash
   cd flask-login-register-system
```


3. Install the required dependencies:

  ```bash
     pip install -r requirements.txt
  ```


## Configuration

1. Open the `config.py` file and configure the following settings:

- `SECRET_KEY`: A secret key used for securely signing session cookies.
- `SQLALCHEMY_DATABASE_URI`: The URI for your database (SQLite, MySQL, PostgreSQL, etc.).
- `SQLALCHEMY_TRACK_MODIFICATIONS`: Set to `False` to suppress SQLAlchemy modification tracking.

## Usage

1. Run the Flask application:

  ```bash
     python app.py
  ```


2. Open your web browser and navigate to `http://localhost:5000` to access the application.

3. Use the provided user registration and login forms to create an account and log in.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Flask: A lightweight WSGI web application framework.
- Flask-Login: Provides user session management for Flask applications.
- Werkzeug: A WSGI utility library for Python.



