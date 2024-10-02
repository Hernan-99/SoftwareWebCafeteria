# Software

# Crear entorno virtual
python -m venv venv

# Activamos el entorno virtual
.\venv\Scripts\activate

# Creamos un proyecto django
django-admin startproject .

# Proyectos de django
dentro de estos podemos tener aplicaciones, por ejemplo la logica de un login o un formulario seria una app

# Creamos aplicacion
python manage.py startapp reservas

# registramos la app creada
vamos a settings.py del proyecto y en Application definition ponemos el nombre de la app