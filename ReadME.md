https://www.youtube.com/watch?v=q7mZq86cH9g

to check python version:
>python --version

to check pip version:
>pip --version

to install django:
>pip install django

to check django version:
>django-admin --version

to create new project 
>django-admin startproject <myfirstweb>
>cd myfirstweb

to run project
>python manage.py runserver

start running on> http://127.0.0.1:8000

https://www.python.org/

https://www.djangoproject.com/

to create new app
>django-admin startapp <mynewapp>


view.py

from django.http import HttpResponse

def homepageview(request):
    return HttpResponse("Welcome to my website")
	
create new file in app > url.py	

