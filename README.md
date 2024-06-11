# Aplicación De Trámite Documentario

Bienvenido a nuestra aplicación de Trámite documentario. Este proyecto está desarrollado en PHP, CSS y JavaScript, utilizando Bulma CSS a través de una CDN para el diseño y estilos. 

## Descripción

Esta aplicación ofrece una plataforma ofrece un servicio para la recepcion de documentos y su posterior tramite a travez de una plataforma donde cada usuario puede ver sus tramites asi como cada usuario de tipo docente ver los trámites que le llegaron.

## Tecnologías Utilizadas

- **PHP**: Para la lógica del servidor y la generación dinámica de contenido.
- **CSS**: Utilizando Bulma CSS para los estilos.
- **JavaScript**: Para la interactividad en el cliente.
- **MySQL**: Como base de datos para almacenar la información.
- **XAMPP**: Para el servidor local durante el desarrollo.

## Instalación y Ejecución en Local

Para ejecutar esta aplicación en tu máquina local, sigue estos pasos:

### Prerrequisitos

- [XAMPP](https://www.apachefriends.org/index.html) instalado.

### Clonar el Repositorio

Clona el repositorio a tu máquina local en la carpeta xamp/htdocs usando el siguiente comando:

```bash
git clone https://github.com/pauldev24/Tramite_Documentario.git

```
## Configurar el Archivo de Conexión a la Base de Datos
- Asegúrate de que los parámetros de conexión en el archivo utils/conexion.php:

```bash
<?php
    $cn = mysql_connect("localhost", "root", "");
    mysql_select_db("tramite2022", $cn);

?>
```
- Para terminar de ejecutar el proyecto solo dirigise en el navegador a localhost/(nombre del proyecto)

## Colaboradores
Este proyecto fue realizado por mi persona como en colaboración con otros compañeros como parte de un proyecto de mi universidad.