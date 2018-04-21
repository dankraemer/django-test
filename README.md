# django-test
Test basic django deploy and application
# Test Log
- Download and install Python 3.6.5
- Test installation:
  $ python --version
  $ pip --version
- Install python virtual environment:
  $ pip install virtualenvwrapper-win
- Create a Virtual Environment:
  $ mkvirtualenv py1 
- To select which virtual env you want to use:
  $ workon py1
- Install django
  $ pip install django
- Create a Django project and open on VS Code
  $ code .
- Run Python server:
  $ python manage.py runserver
- Check on Browser http://localhost:8000 
- Install MySQL support for Python
  $ pip install mysqlclient
- Modify settings.py with MySQL database info:
  - Add user, password, host, port
- Create MySQL tables:
  $ python manage.py migrate
- Run Python server with new features:
  $ python manage.py runserver
- Check on Browser http://localhost:8000/admin
- On terminal, create a superuser:
  $ python manage.py createsuperuser --username=dka --email=dka@gmail.com
- Create an Application
  $ python manage.py startapp posts
