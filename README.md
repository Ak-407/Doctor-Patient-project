## See the Vedio Demonstration 
# Doctor-Patient-project
1. First install django using pip
2. Create Django Project
bashdjango-admin startproject myproject
cd myproject
python manage.py startapp accounts


3. Run Migrations
bashpython manage.py makemigrations
python manage.py migrate


4. Run Server
bashpython manage.py runserver

5. Access the Application
Signup: http://127.0.0.1:8000/signup/
Login: http://127.0.0.1:8000/login/ --> it will redirect to the profession you choose in signup.
