# Profiles REST API

Profiles REST API course code.

## Instructions

* Install Vagrant and virtual Box, and git bash terminal
* Create the vagran file by typing `vagrant init generic/ubuntu2204`
* Change the config of the created file according to your needs.
* Run the server by typing `vagrant up`
* Connect to the server by typing `vagrant ssh`
    * You can exit the server using the command `exit`
* Once inside, move to the project folder by typing `cd /vagrant`.
* Create the virtual enviroment in your vm home directory: `python -m venv ~/env`
    * To Run the venv, type: `source ~/env/bin/activate`
* Install the required packages by typing: `pip install -r requirements.txt`
* To start the project run: `django-admin startproject [name-of-the-project] [location]`
* To create an app run: `python manage.py startapp [name-of-the-app]`
* Enable the apps by adding them to de settings.py file
* To test that everything is up and running run the code: `python manage.py runserver 0.0.0.0:8000`
    * Access to the server by typing in your web browser: `127.0.0.1:8000`