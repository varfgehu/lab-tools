Preparations:
-------------

1, install requirements
2, django-admmin startproject lab_tools <name of the project>
3, cd lab_tools
4, django-admin startapp api
5, Open settings.py, navigate to INSTALLED_APPS, add 'api.apps.ApiConfig'
6, Open settings.py, navigate to INSTALLED_APPS, add 'rest_framework'
7, Create new file "urls.py" in the api folder
8-9, Set up api views.py with a main(response) func to return HttpResponse("hello") and set up urls.py in api with a path('', main) (any endpoint in /api will be directed to main function)

10, python manage.py makemigrations, to initialize the database
11, python manage.py migrate
12, python manage.py runserver, start your first django application

