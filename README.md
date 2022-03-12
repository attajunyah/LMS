# LMS
Django LMS is a Learning Management System using the framework, you guessed it right, Django. The system gives students and parents a simple platform to learn online through tutorial videos. They can download presentations, lecture notes and videos if they want to. 

# Motivation
The project started as a challenge to improve and test my knowledge of Django. The initial version of this project was created with vanilla JavaScript, PHP, HTML, CSS and Bootstrap. 

# Tech/Framework Used
* Python
* Django
* HTML
* CSS
* Bootstrap

# Features
This platform is fairly simple yet provides most of the necessary features required in a Learning Management System. It uses Django's MTV architecture.
* Signup
* Login
* Logout
* Course Creation
* Course Deletion
* Class Scheduling 
* Comments and Replies
* Assignment Deletion
* Download Lecture Resources

## Configuration
Configuration is stored in `src/app/.env`, for examples see `src/app/.env.ci`

## Installing on a local machine
This project requires python3.8 and sqlite.

Install requirements:

```sh
cd src && pip install -r requirements.txt
cp app/.env.ci app/.env  # default environment variables
```

```sh
./manage.py migrate
./manage.py createsuperuser
```

Testing:
```bash
# run unit tests
$ pytest
```

Development servers:

```bash
# run django dev server
$ ./manage.py runserver

```
