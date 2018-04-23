my_django_start_default
=======================

Windows:

.. code-block:: console

   set PROJECT_NAME=my_project_test
   set SECRET_KEY=123456
   set DEBUG=True
   
   virtualenv %PROJECT_NAME%
   cd %PROJECT_NAME%
   Scripts\activate
   pip install "django<2"
   django-admin startproject --template=https://github.com/TiagoDGomes/my_django_start_default/archive/master.zip  %PROJECT_NAME%
   cd %PROJECT_NAME%
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   
   
   
