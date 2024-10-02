# SoftwareWebCafeteria

# Creacion de entorno virtual
python -m venv venv

# activar entorno
.\venv\Scripts\activate

# instalar django en el entorno virtual
pip install django

# Crea el proyecto Django
django-admin startproject nombre_del_proyecto .

# dentro del proyecto creamos una aplicacion django
python manage.py startapp softwarecafeteriaaplicacion

## Descripcion:
django permite como crear una carpeta general (seria el proyecto) y dentro de esa podemos tener aplicaciones, es decir si tenemos un proyecto que trata de una web con login, blog y demas las aplicaciones seria el login, el blog, etc. Modularizamos apps
