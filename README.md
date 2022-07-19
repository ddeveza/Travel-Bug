#  Travel Bug Forum App in React & Redux + Django

```
Visiting USA? This virtual guide is extremely handy, you can scan the entire area
in USA and find invaluable information of major attractions, places of interest,
events, museums, plays, and probable locations of rare species of wild animals which 
you may be lucky enough to get a glimpse of! With this app, you can easily navigate your
visit to USA!
```

## Live Demo

**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**

Check out [FRONTEND LIVE DEMO](https://travel-bug-frontend-gd.herokuapp.com/) here!!

Check out [API LIVE DEMO](https://travel-bug-backend-gd.herokuapp.com/) here!!

## Tech used

```
* Frontend : React & Redux
* Backend : Django
```

## How to Install

1. Git Clone

```
git clone https://github.com/Travel-Bug-techis/Travel-Bug.git
```

2. Backend setting

```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```

3. Frontend setting

```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
