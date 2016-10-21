# {{ pinax_project }}

## Getting Started

Install virtualenv and add virtualenv enviroment
```
pip install virtualenv
virtualenv mysiteenv
source mysiteenv/bin/activate
```

Install Django and clone this project to local:
```
pip install Django==1.8.4
git clone git@github.com:oceanpad/pinax-p.git
```

Make sure you are using a virtual environment of some sort (e.g. `virtualenv` or
`pyenv`).

```
pip install -r requirements.txt
./manage.py migrate
./manage.py loaddata sites
./manage.py runserver
```

* if you want to access this server remotely, run use `0.0.0.0:8000` parameter:
```
./manage.py runserver 0.0.0.0:8000
```
