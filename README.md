Project Overview

This project is a Flask-based web application for teachers to manage their work, including functionalities such as user registration, login, tracking payments, checking attendance, and managing report cards. The project structure and necessary imports ensure smooth functioning by leveraging various Flask extensions.

Project Structure

Here is the project structure for reference:

<img width="284" alt="Screenshot 2024-07-03 at 11 52 38 PM" src="https://github.com/infinite2004/myschool/assets/44120607/1604cfc0-2dc8-4c2c-bea4-4099065f95e5">


File Descriptions

	1.	app.py: Main application file initializing Flask, database, login manager, and routing.
	2.	config.py: Configuration settings for the Flask application.
	3.	extensions.py: Initializing extensions like SQLAlchemy and LoginManager to avoid circular imports.
	4.	forms.py: Defining WTForms for registration and login.
	5.	models.py: Defining SQLAlchemy models.
	6.	templates/: HTML templates for rendering pages.
	7.	static/: Static files like CSS.


    Ensure you have the correct dependencies in requirements.txt:
   
    Flask==2.0.2
    Flask-SQLAlchemy==2.5.1
    Flask-Login==0.5.0
    Flask-WTF==0.14.3
    email-validator==1.1.3
    Werkzeug==2.0.2
    Jinja2==3.0.1
    SQLAlchemy==1.4.22


Setting Up and Running the Project:

 1.	Create a virtual environment:

    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`


 2.	Install dependencies:


    pip install -r requirements.txt


3.	Run the application:

    python app.py



