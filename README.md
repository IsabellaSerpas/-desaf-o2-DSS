o Instrucciones de instalación y uso.

1. Clona el repositorio o descarga los archivos.
2. Copia la carpeta del proyecto en `C:\wamp64\www\` si estás usando WAMP.
3. Exporta la base de datos en phpMyAdmin que se encuentra dentro de la carpeta del proyecto.
4. Abre tu navegador y visita: `http://localhost/app/views/registro.php`
5. Desde ahí puedes subir, visualizar y eliminar archivos fácilmente.

o Descripción de la estructura de clases.

- `subir.php`: Permite subir archivos al servidor y guarda el nombre en la base de datos. También permite eliminar archivos y su registro en la base de datos y se muestran los archivos almacenados en una lista interactiva.
- `db.php`: Hace la conexión a la base de datos en phpMyAdmin.
- `auth.php`: hace una autenticación a la base de datos verificando si el usuario ha sido registrado anteriormente.
- `archivero`: es la carpeta donde se almacenarán cada uno de los documentos almacenados.
- `dashboard.php`: Es donde da la opcion de subir el archivo a almacenar.
- `archivos.php`: Es el que permite guardar y eliminar  los archivos en la base de datos.
- `usuario.php`: Es el que se encarga de registrar y guardar el usuario creado en la base de datos, ademas de comparar el user ingresado con los registrados en la base de datos
-`logout.php`: permite cerrar la sesión.
-`index.php`: Hace la funcion de redirirgir, si en dado caso el usuario ingresado es congruente con los almacenado en la base de datos y si no, este muestra un mensaje de credenciales invalidas, y si no está bien ingresado este muestra un error de error al registrar.
-`login.php`: es la vista para el ingreso de usuario ya existente.
-`registro.php`: es la vista para crear un nuevo usuario.

o Roles asumidos por cada integrante.

-Alexandra Raquel Rodríguez Majano RM240112
Desarrolladora

-Amanda Isabella Serpas Rivera SR240105
Desarrolladora



