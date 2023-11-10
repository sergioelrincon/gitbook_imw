# Introducción

## Contenidos

* [Instalación y configuración de Apache, PHP y MySQL en Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04)
* Creación de base de datos, usuario y asignación de permisos en MYSQL\
  `CREATE USER 'alumnado'@'localhost' IDENTIFIED BY 'Elrincon1234.';`\
  `FLUSH PRIVILEGES;` \
  `CREATE DATABASE alumnado_db;` \
  `GRANT ALL ON alumnado_db.* TO 'alumnado'@'localhost';`\
  `FLUSH PRIVILEGES;`\
  \
  La contraseña es "Elrincon1234."\
  "alumnado" es el nombre de usuario\
  "alumnado\_db" es el nombre de la base de datos
* [Instalación de PHPmyAdmin](https://ubuntu.com/server/docs/how-to-install-and-configure-phpmyadmin)
