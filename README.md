# Django-React Todo App

This application is a simple Todo App over-engineered with `django` as a backend and `restframework` for API.

## Technologies

Backend:
- django = `4.1.6`
- django-cors-headers = `3.13.0`
- djangorestframework = `3.14.0`

Frontend:
- axios = `^0.21.1`
- bootstrap = `^4.6.0`
- react = `^18.2.0`
- react-dom = `^18.2.0`
- reactstrap = `^8.9.0`

## Installation

**For Backend:**

- `cd` into the root folder and install dependencies using `pipenv`

```
cd django-todo-app
pipenv install
```
- then you can `cd` into `backend` and run the django server
```
cd backend
python manage.py runserver
```
> You will find your backend running on [http://127.0.0.1:8000/api](http://127.0.0.1:8000/api)

**For Frontend**
- `cd` into `frontend` and install javascript dependencies
```
npm install
```
- then you can start the client by using the following
```
npm run dev
```
> You will find your frontend running on [http://127.0.0.1:5173](http://127.0.0.1:5173)