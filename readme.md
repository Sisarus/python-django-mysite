# first django app

## Needed Technologies

* python
* docker

### create django app
```
python -m django startproject mysite
```
### startapp firstapp
```
python manage.py 
```
### migrate tables

makemigrations
```
python manage.py migrate
```
### run docker
```
docker compose up --build
```

### Run app
```
python manage.py runserver
```

#### Notes
```
pip install pipreqs
pipreqs .
```

### Links
* http://127.0.0.1:8000/firstapp/
* http://127.0.0.1:8000/firstapp/date