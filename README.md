# texteditor

## setup conda env

```sh
conda create --name <env> --file richtext-env.txt
```

## install packages

```sh
python -m pip install -r requirements.txt
```

## Run Migration

```sh
python manage.py migrate
```

## Create admin user

```sh
python manage.py createsuperuser
```

## start project

```sh
python manage.py runserver
```

## Demo

navigate to this url `http://127.0.0.1:8000/admin/demo/student/`

from the text editor you can add text and images as per your needs
