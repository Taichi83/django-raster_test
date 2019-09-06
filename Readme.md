```
$ docker-compose build
$ docker-compose run app django-admin startproject geodjango .
$ docker-compose up -d
$ docker-compose run app python manage.py migrate
$ docker-compose run app python manage.py runserver
$ docker exec -it app_test bash
$ docker-compose run -p 8083:8083 --name=app__test_run app bash
# jupyter notebook --generate-config
# jupyter notebook password
# jupyter lab --ip=0.0.0.0 --port=8083 --allow-root
```