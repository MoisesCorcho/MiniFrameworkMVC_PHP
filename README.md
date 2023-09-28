# MiniFrameworkMVC

Es un proyecto que podria describirse como un "MiniFramework" (por ello su nombre) creado en php bajo el patron MVC.

El flujo de trabajo para el uso de este framework consta de:
- Establecer las variables de configuracion del proyecto (dentro de app/config/config.php)
- Crear un controlodar (dentro de la ruta app/controladores)
- Crear un modelo (dentro de la carpeta app/models) para que el controlador pueda comunicarse con la base de datos 
- crear vistas (dentro de la ruta app/models)


Para configurar tu proyecto, sigue estos pasos:

## Configuración de la Base de Datos

En el archivo `app/config/config.php`, establece la configuración de tu base de datos, la URL y el nombre de tu sitio:

## Configuración de la Ruta del Proyecto

En el archivo .htaccess dentro de la carpeta public, establece la ruta del proyecto en YOUR_PROJECT_PATH.
Usé XAMPP para la realizacion de este proyecto, con lo cual, en YOUR_PROJECT_PATH iria la ruta de tu proyecto luego de 
la carpeta htdocs

