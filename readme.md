## LOGIN CON LARAVEL

Este es un proyecto que ya puedes descargar y iniciar el tuyo sin necesidad de hacer el login ya esta listo solo para usar. cuenta con las siguientes caracteristicas.

- Vistas
- Controlador
- Modelo
- Registrar usuario
- Recuperar contraseña
- Recordar usuario
- Cerrar seccion

## PASOS PARA IMPLEMENTAR

Primero descarga el proyecto, despues tomamos el archivo login.sql que es la base de datos y lo importamos en nuestra base de datos, para ellos debmos seguir los siguientes pasos:

- Abrimos nuestra base de datos, si usas MYSQL y xampp debes tener instalado PHPMYADMIN, la ruta habitual es http://localhost/phpmyadmin.
- Creamos la tabla login.
- Vamos a la parte de importar, seleccionamos el archivo login.sql y damos continuar.

Despues de tener el proyecto en la carpeta htdocs o www, segun la aplicacion que uses
xampp o wampp. Debemos abrir la consola y ejecutamos lo siguiente:

```
php artisan key:generate
```

Seguido por el siguiente comando:

```
php artisan migrate:fresh
```

Por ultimo solo es abrir el proyecto en el navedador y usarlo.

## License

Libre.
