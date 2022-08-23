# Aprendiendo-Django
Este repositorio se encuentra todo mis apuntes y proceso de aprendizaje sobre el framework Django

![image](https://user-images.githubusercontent.com/111031732/186083552-8906a54c-417d-4254-a8f4-0d43a3a4a1a2.png)

## Inciar proyecto en Django
En la consola de comando en la ruta donde se realizará el proyecto se usa el siguiente codigo para comenzar a Usar Django

`
django-admin startproject "NombreDelProyecto"
`

**Nota:** Todo lo que se coloque entre comillas dobles indica lo que debe ir en ese lugar, pero no es su sintaxis tal cual

## Comando con manage

Cuando se crea un proyecto en Django se crea un fichero llamado 'manage.py' el cual es una utilidad en linea de comando.

`
python manage.py help
`

Esto nos enseña todos los mando que que se puede utilizar con 'manage.py' desde la consola

## Comandos generales

**Runserver**

`
python manage.py runserver
`

Corre el servidor de Django para la web, si no se está corriendo no servirá la web.

**Migrate**

`
python manage.py migrate
`

Genera una base de datos con las funcionalidades que funcionan por defecto en django (db.sqlite3).
