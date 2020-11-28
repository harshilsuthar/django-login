# django-login
login app for project

do first migration of django project to create django default models.

add nevigation folder into your project.

add "nevigation" in "installed app" in settings.py

add 'nevigation/' path and include('nevigation.urls') to project/urls.py file.

go to nevigation/login in browser for login page

go to nevigation/register for register page

go to nevigation/logout for logout.

go to loginView in views.py, line 19(return redirect('myapp:ConnectServer')) is redirect to login success page.

change it according to your project requirement.
