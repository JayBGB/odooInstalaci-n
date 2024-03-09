# Instalación de Odoo
## Con Docker y Docker Compose
En primer lugar, debemos asegurarnos de que tenemos una instalación válida de Docker. Una vez estemos seguros de ello, utilizaremos PyCharm para trabajar en nuestro `docker-compose.yml`.

## 1. docker-compose.yml

![Estructura del docker-compose](capturas/compose.png "docker-compose.yml")

Tal y como podemos apreciar en la imagen, utilizaremos la imagen Odoo 16.0. También se puede comprobar el cliente de bases de datos que utilizaremos, que en este caso será PostgreSQL.

## 2. Configuración de PostgreSQL

> [!IMPORTANT]
> Para llevar a cabo este paso, antes es necesario levantar nuestro Docker con el comando `docker compose up -d`.

![Configuración BD](capturas/db.png "Configuración BD")

Rellenamos los campos necesarios con nombre de usuario y contraseña, asegurándonos de que el puerto es el correcto así como la base de datos. Podemos comprobar que la conexión es exitosa y, acto seguido, aplicar los cambios y aceptar.
