# Proyecto

### Dependencias necesarias

sudo apt-get install python3

sudo apt-get install python3-pip

pip3 install Pillow

sudo apt-get install apache2 libapache2-mod-wsgi-py3

pip3 install django==2.2.17

sudo apt-get install python-django python-django-common

sudo apt-get install postgresql postgresql-contrib

sudo apt-get install postgresql-client postgresql-client-common

sudo apt-get install libpq-dev python-dev

pip3 install psycopg2

pip3 install djangorestframework

### Configuración Base de Datos

sudo -u postgres psql

(#) \password postgres (Ingresamos la nueva contraseña: password)

(#) \q (para salir)

sudo -u postgres createdb andb

### Levantar el proyecto

(Dentro de la carpeta aduana)

python3 manage.py makemigrations

python3 manage.py migrate

python3 manage.py runserver
