# JimPintoMiniProject04

# Recipe Keeper Web App

**INF601 - Advanced Programming in Python**  
**Jim Pinto**  

## Description
This project uses Django to deploy a small web application called Recipe Keeper. Users can register, log in, and save their favorite recipes, allowing them to create, view, and manage a personal collection of recipes categorized by type.

## Getting Started

### Dependencies
To install the required packages, run:
pip install -r requirements.txt
Executing the Program
Initialize the Database: Before running the project, make sure to create the necessary database tables and superuser account by running the following commands:

Copy
Edit
python manage.py makemigrations  # This will create any SQL entries that need to go into the database
python manage.py migrate           # This will apply the migrations
python manage.py createsuperuser   # This will create the administrator login for your /admin side of your project
Run the Development Server: Start the server with:

Copy
Edit
python manage.py runserver
Access the Application: Open your web browser and visit http://127.0.0.1:8000/ to use the Recipe Keeper app.

Output
This web application allows users to manage recipes, and you can access the admin panel at http://127.0.0.1:8000/admin using the superuser credentials you created.

Authors
Jim Pinto
Email: your.email@example.com

Acknowledgments
Inspiration and code snippets from Django documentation and community forums.

Libraries used:

Django

Bootstrap for styling
