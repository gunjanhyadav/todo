# Project Title 
Todo Application
The application is built on django using its restframework.

# Core features
The user can do the following: GET, POST, PUT, DELETE and RETRIEVE the items.

# Prerequisites
- Python3
- django
- djangorestframework

# Installing

- After installig the Python3, download the project in you local machine.

# Virtual environment (optional but recommended)
- Go to the folder and install virutal environment using 

  ```
  pip install virtualenv
  ```
  
 - Create virtual environment using
 
  ```
 virtualenv venv (name_of_venv)
  ```
 
 # Run requirements.txt file
 Run the code in your terminal to get the requried libraries using 
 
 ```
 pip install -r requirements.txt
 
 ```

 # Migrations 
 Run the following code lines in your terminal 

 ```
  python manage.py makemigrations
 ```
 
 ```
  python manage.py migrate
 ```

 
 # Create superuser 
  ```
     python manage.py createsuperuser
  ```
 
 # Run project
 Run the following code in your terminal 
 
 ```
 python manage.py runserver
 ```
 Then go to http://127.0.0.1:8000/ in your browser, Its Done!
 "todos": "http://127.0.0.1:8000/api/v1/






