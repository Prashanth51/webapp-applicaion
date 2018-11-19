# webapp-applicaion
To store  the student details
installed python v 3.6
install django v 1.11.9
created a folder in D drive called Gramener Test
created a project 'webapp' using 'django-startproject webapp' command using command prompt
start app name with 'myapp' using python manage.py startapp myapp command.
open Gramener Test Folder using Atom editor
open settings.py file  and add 'myapp' to 'INSTALLED_APPS'
open webapp folder under Gramener Test
open myapp >open models.py file
created Student model
configure the migrations using py manage.py makemigrations and py manage.py migrate
then open admin.py file and register the model to the admin site
created template folder under myapp under that created html file 
open views.py file and created views for html files
open urls.py file and configure the url patterns
opened command prompt typed py manage.py run server 
opened web browser type url http://127.0.0.8000 or http://localhost:8000
clik link and add the student details if click submit button   it will display all details what ever we inserted 
** we can also  store student details by using admin interface
