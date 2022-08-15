# flask tuitorial project for GitHub Actions

https://msiz07-flask-docs-ja.readthedocs.io/ja/latest/tutorial/index.html

# env

- WSL2 Ubuntu 20
- Python3.10

## create venv

https://msiz07-flask-docs-ja.readthedocs.io/ja/latest/installation.html

```
$ mkdir xp-ci-flask-tutorial
$ cd xp-ci-flask-tutorial
$ python3.10 -m venv venv
$ source venv/bin/activate
```

## Flask install

```
$ pip install Flask
```

## run application

```
$ export FLASK_APP=flaskr
$ export FLASK_ENV=development
$ flask run
```

## init db

```
$ flask init-db
```

## project install

```
$ pip install -e .
```

## for testing

```
$ pip install pytest coverage
```

```
$ coverage run -m pytest
$ coverage report
$ coverage html
```