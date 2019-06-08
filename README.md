# Django

## Create a Project
```sh
$ django-admin startproject myproject
```
This will create a "myproject" folder with the following structure − 

```sh
myproject/
   manage.py
   myproject/
      __init__.py
      settings.py
      urls.py
      wsgi.py
```
# The Project Structure 

The “myproject” folder is just your project container, it actually contains two elements − 

  -- manage.py − This file is kind of your project local django-admin for interacting with your project via command line (start the development server, sync db...). To get a full list of command accessible via manage.py you can use the code −
