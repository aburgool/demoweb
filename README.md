This is another Django Demo Application.

This particular one shows you how to reuse Django Admin Templates.
How-To, you need:

- ptyhon 3.6 (3.x will be fine)
- django 3 (any 1.x, 2.x will be fine)
- create your venv as usual with python 3.x
- pip install -r requirements.txt (as usual)

I've created my python venv as:
- python -m venv pyenv (or .pyenv)

Then create your django-admin startproject demoweb.
Then cd into demoweb and startapp demoapp as:
- cd demoweb && python manage.py startapp demoapp

Of course feel free to clone this project to avoid previous steps :-)

The demoapp/templates/demoapp/base.html as the key, it will extend from admin:base.html and override some django template blocks, that's all !

enjoy !

PD: there is a simple index.html style guide once you run the django dev server as:
- python manage.py runserver

![demoapp template](/demoweb/demoapp/static/demoapp/img/demoweb.png)