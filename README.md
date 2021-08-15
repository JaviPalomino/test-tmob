# TMOB - Javier Palomino
## Pasos a ejecutar
- Crear entorno virtual con python3
- instalar requirements : pip install -r requirements.txt
- migraciones: python manage.py makemigrations y python manage.py migrate
- Crear el admin user: python manage.py createsuperuser
- Se pueden crear registros desde el admin :)
- La configuracion de DB y cache  deben hacerlo en el archivo .envs/.config, el settings.py toma de este archivo.
- url de endpoint : /api/v1/get/<key>
- para ejecutar los test: python manage.py test
- Se testeo el endpoint con POSTMAN



**Disfrute el ejercicio, Gracias!**

