Book A Meal 
=======


## API Endpoints covered included in this branch


| Method        |       Endpoint                              |         Description                           |
| ------------- |       -------------                         |         -------------                         |
| `GET`         | `/api/v1/...`                  |   Gets all  records                    |
| `GET`         | `/api/v1/.../<int:id>`               |   Get a specific  record                |
| `POST`        | `/api/v1/...`                           |   Create a record                       |
| `POST`        | `/api/v1/auth/registration`                |   Register a user                             |
| `POST`        | `/api/v1/auth/login`                       |   Sign in a User                              |



# Setting up your system

Make sure you already have Python3 and pipenv installed. Check that python 3.6.x is installed and pipenv:

```
python --version
Python 3.6.9

```

Install pipenv:
```
pip3 install pipenv
```

Check pipenv is installed

```

pipenv --version
pipenv, version 2018.11.26
```

## Getting started

Start by making a directory where we will work on. Simply Open your terminal and then:

```
mkdir Book-a-meal
```

Afterwhich we go into the directory:

```
cd Book-a-meal
```

clone the project
```
git clone https://github.com/Bakley/Book-a-meal.git .  --> Remember the dot
```

Then spawn a shell

```
pipenv shell
```

```
pipenv lock
```

Install dependancies

```
pipenv sync
```




## Testing
To test the endpoints ensure that the following tools are available the follow steps below
### Tools:
    Postman

### Commands
  The application is tested using coverage. To run the tests on the bash terminal use

     coverage run --source='.' manage.py test the-app-you-want-to-test  && coverage report
