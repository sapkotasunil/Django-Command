# Django-Command
Here is the all basic  Django command that is useful for beginner 


**Create a folder for your project :**
mkdir myproject

**Move to the folder for your project :**
cd myproject

**Create a virtual environment :**
python -m venv venv

**Activate the virtual environment :**

   **On Windows:** venv\Scripts\activate
   
   **On macOS/Linux:** source env/bin/activate

**Install Django :**
pip install django

**Start a Django project in the current folder :**
django-admin startproject main .

**Run the development server :**
python manage.py runserver

**Create a new Django app :**
python manage.py startapp myapp

**Apply initial database migrations :**
py manage.py makemigrations
python manage.py migrate

**Create a superuser (admin) :**
python manage.py createsuperuser

Run the server again and access admin panel :

python manage.py runserver

Open in browser: http://127.0.0.1:8000/admin/

**when clone the code from git and install all dependencies :**
pip install -r requirements.txt
