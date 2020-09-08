# INICIANDO CON DJANGO PYTHON 3.8.2

<h1> Descargar python e instalarlo Version actual</h1>
https://www.python.org/downloads/

- para saber que version tienes al descargarlo.
```sh
python --version
```

<h1> Descargar env para python. </h1>
```sh
pip install env
```

<h1> Generando entorno en tu carpeta preferida.</h1>
```sh
python -m venv env
```

- ejecutar env (Windows).
```sh
source env/Scripts/activate
```

- ejecutar env (linux).
```sh
source env/bin/activate
```


<h1> Descargar django en el entorno virtual.</h1>
```sh
pip install django
```

- saber la version de django.
```sh
python -m django --version
```

- generando archivos para proyecto.
```sh
django-admin startproject mysite
python manage.py startapp polls
```
