# flash_news_v2

A news aggregator website where user can read/view politics, sports, and tech news in one website.

## Snapshot

### Mobile View

Mobile Navbar | Home | 
:---------:|:--------:
<img src="https://user-images.githubusercontent.com/25072657/33098781-69f7a42e-cec3-11e7-9d42-1ce515dd5e08.png" width="100%"> | <img src="https://user-images.githubusercontent.com/25072657/33098838-908729c0-cec3-11e7-86b3-bca929de2df6.png" width="60%">

### Desktop View
<img src="https://user-images.githubusercontent.com/25072657/33117706-51f52d1e-cf1e-11e7-85a0-f6a32740ad40.png" width="75%">

## Prerequisites/Installing

To open Django project, please install django 1.11 and latest python 3.6 (or latest) turn on virtual environment on your terminal/bash

For Mac/Linux Users, please install python through [homebrew](https://brew.sh/)

For Windows Users, please install python [here](https://www.python.org/downloads/release/python-2713/)

```
#Create new directory called myEnvironments(or any name you want) and navigate there.
EX: $ cd ~/Documents/sser/python_stack/myEnvironments

#Mac/Linux
brew update #updates homebrew
brew install python #install python
pip install virtualenv 

#Inside the myEnvironments folder, create your first virtual environment
virtualenv djangoEnv(or name it whatever you want)

#On folder where your virtualEnvironment(s) are located at
source djangoEnv/bin/activate

#Windows
python -m virtualenv djangoEnv(or name whatever you want)

#Inside the myEnvironments folder, create your first virtual environment
virtualenv djangoEnv(or name it whatever you want)

#Choose of the following depending on your Windows command or git bash:
call djangoEnv/Scripts/activate #Windows command prompt
. djangoEnv/Scripts/activate #Windows 10 command prompt
source djangoEnv/Scripts/activate #Windows git bash


#All Users - after virtual environment is activated, install latest Django Version
pip install Django==1.11
```

## Opening the project (locally) to view the site.

Go to the project folder where it contains manage.py through your terminal/command and type:

```
python manage.py runserver
```

Once activated, you can browse to localhost:8000

## Built With

* [Python](https://www.python.org/) - Backend language used
* [Django](https://www.djangoproject.com/) - The web framework used
* [SQL](https://www.sqlite.org/) - Used to manage database

## Authors

* **Steve Kim** - [Suykim21](https://github.com/Suykim21)
* **Jake Kiernan** - [jakekiernan](https://github.com/jakekiernan)
