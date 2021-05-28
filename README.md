
PYTHON API USER TEST GUIDE

Make sure python and pip is installed else download from  Welcome to Python.org  and included in your environment variables 

how to install the environment and configuration
	1. pip install virtualenvwrapper-win
	2. git clone git://github.com/davidmarble/virtualenvwrapper-win.git into a repository
	3. cd into the repository e.g. "virtualenvwrapper"
	4. run terminal or cmd from this repository (virtualwrapper)
	5. run python setup.py install  in the terminal
	6. Done!

Create a virtualenv using  virtualenvwrapper
Let create a  project folder called test (On desktop)
1. open cmd inside test folder
2. type "mkvirtualenv test_env"  (this folder get activated automatically),  type in cmd without the quotes
3. to activate the virtual env created in case it does not activate by default, use "workon test_env" without the quotes
4. Done.

How to run the project. 
1. clone the project into your desired directory, in our case "test" folder
2. open terminal from the "test" folder and do the following:
3. cd into the "cloned directory name"
```
pip install django 
pip install djangorestframework
pip install django-rest-knox
```
4.  python manage.py runserver
5. open browser and copy localhost:8000 and run
6. Done


How to run angular project
download and install nodejs from  https://nodejs.org/en/download/
1. npm install -g @angular/cli
2. create a directory called auth on your desktop 
3. clone the project into this directory
4. cd into the cloned directory
5. run npm install in this same directory
6. run ng serve
7. copy localhost:4200 into your browser and test the app while the python api is already running.
8. Done