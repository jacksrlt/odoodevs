# Módulo Lista de Tareas

## Odoo Scaffold

Utilizando el comando de Odoo Scaffold se pueden crear módulo para Odoo con la estructura predeterminada de forma rápida.

En la carpeta contenedora de odoo-bin (en este caso la carpeta odoo14) he ejecutado el siguiente comando:

`./odoo-bin scaffold lista_tareas /opt/odoo/odoo14-custom-addons`

Se ha creado una carpeta de nombre "lista_tareas" en la carpeta "odoo14-custom-addons" con la siguiente estructura:

![Estructura de archivos](/img/estructura.png)

Luego lo he subido a la rama devel1 de mi repositorio de Github

![Rama devel1](/img/devel1branch.png)

He excluido algunos ficheros y archivos que no son necesarios o pueden contener datos sensibles en el archivo .gitignore

![Archivo .gitignore](/img/gitignore.png)

## Visual Studio Code

Con la herramienta VS Code accedo a los archivos del módulo para poder trabajar comodamente. Para darle funcionalidad al módulo he modificado los archivos con el código del ejemplo dado en el aula virtual

## \_\_manifest\_\_.py
Incluye información como el título, descripción y ficheros a cargar. Odoo Scaffold crea una estructura predeterminada que hay que descomentar para utilizar.

## models.py
El modelo de datos y sus campos.

## views.xml
Describe las vistas del módulo.




