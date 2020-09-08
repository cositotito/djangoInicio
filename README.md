# INICIANDO CON DJANGO PYTHON 3.8.2

# Descargar python e instalarlo Version actual

- pagina oficial para descargar python
https://www.python.org/downloads/

- Version que tienes al descargarlo.
```sh
python --version
```

- Descargar env para python.
```sh
pip install env
```

- Generando entorno en tu carpeta preferida.
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
