# TodoList-Application
ToDo List App is a kind of app that generally used to maintain our day-to-day tasks or list everything that we have to do,
with the most important tasks at the top of the list, and the least important tasks at the bottom. It is helpful in planning 
our daily schedules.


Step 1: Set Up Your Virtual Environment and Django
Create a Virtual Environment and a Project Directory
      C:\> mkdir projects\todo_list
        
      C:\> cd projects\todo_list
        
      C:\> python -m venv venv
         
     C:\> venv\Scripts\activate.bat
         
The first line creates your virtual environment in the subdirectory venv/. It also copies pip and setuptools into it. 
The second line activates the virtual environment,and your console prompt may change to remind you of that fact.

Install and Test Django

        : (venv) C:\> python -m pip install django=="3.2.9"
      


Step 2: Create Your Django To-Do App
      Generating the parent project framework
      Creating the web app’s framework
      Integrating the web app into the project

Scaffold the Parent Project   :   (venv) C:\> django-admin startproject todo_project .

Get Started on Your Django To-Do List App

(venv) C:\> django-admin startapp todo_app

Step 3: Design Your To-Do Data
Define Your Data Models

Create the Database
(venv) C:\> python manage.py makemigrations todo_app
(venv) C:\> python manage.py migrate

Step 4: Add Your Sample To-Do Data
 1.Meet the Django Admin Interface  -  (venv) C:\> python manage.py createsuperuser

 2.make sure the development server is running:  (venv) C:\> python manage.py runserver

Start a To-Do List



 


