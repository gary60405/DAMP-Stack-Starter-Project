# DAMP Stack Starter Project
## List of integrated packages
As the below list, It had integrated packages for deploying and building restful API.
* psycopg2-binary
* django-heroku
* gunicorn
* django
* djangorestframework

## Prerequisites
* Yarn 1.22.4
* Angular CLI 10.0.0
* Node 12.18.1
* MySQL 5.7
* Python 3.8.3
    * pipenv 2020.6.2 
## Usage
### Step.1 
Clone the project. 
```git
$ git clone https://github.com/gary60405/DAMP-starter-project.git
```
### Step.2
Launch the `cmd.exe` and type the text below for installing all the node_modules.
```
$ cd frontend
$ yarn install
```
### Step.3
Launch the `cmd.exe` and type the text below for installing all the packages.
```
$ cd backend
$ pipenv install
```
### Step.4
Open `backend/backend/setting.py`
```python
# Generating SECRET_KEY here: https://djskgen.herokuapp.com/
SECRET_KEY = ''

# Filling in the empty fields
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': '', # schema_name
        'USER': '', # user_name
        'PASSWORD': '', # login_password
        'HOST': 'localhost', # localhost or 127.0.0.1
        'PORT': '3306',
    }
}
```


## License
MIT license