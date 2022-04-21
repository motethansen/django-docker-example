# Simple Django Hello World Starter Template

Original repository is from [LondonAppDev](https://github.com/LondonAppDeveloper/demo-django-hello-world-starter), who also explain the docker process in this [video](https://youtu.be/nh1ynJGJuT8)


A basic Django 3.0 starter project.


## Usage

 1. Using Python 3.8, run `python -m venv env` to create a virtual environment
 2. Run `pip install -r requirements.txt` to install dependencies
 3. Run `cd app/` to change to `app/`
 3. Run `python manage.py runserver` to start development server
 4. Navigate to [http://127.0.0.1:8000](http://127.0.0.1:8000) to test

---

run the local docker image with the command

```
$ docker-compose -f docker-compose-local.yml up --build
```