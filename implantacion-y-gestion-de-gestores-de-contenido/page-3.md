# Introducción

## Recursos

* [Manejo de servicios en Ubuntu](https://conocimientolibre.mx/servicios-ubuntu/)
* [How to solve PhpMyadmin Access Denied](https://skinnyboys.medium.com/how-to-probleme-solve-phpmyadmin-access-denied-2679685f5ef0)

## Contenidos

* [Instalación de Apache](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04#step-1-installing-apache-and-updating-the-firewall)
* [Instalación de MySQL](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04#step-2-installing-mysql)
* [Instalación de PHP ](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04#step-3-installing-php)
* Creación de base de datos, usuario y asignación de permisos sobre dicha base de datos\
  \
  `CREATE USER 'alumnado'@'localhost' IDENTIFIED BY 'Elrincon1234.';`\
  `CREATE DATABASE alumnado_db;` \
  `GRANT ALL ON alumnado_db.* TO 'alumnado'@'localhost';`\
  `FLUSH PRIVILEGES;`\
  \
  La contraseña es "Elrincon1234."\
  "alumnado" es el nombre de usuario\
  "alumnado\_db" es el nombre de la base de datos
* [Instalación de PHPmyAdmin](https://ubuntu.com/server/docs/how-to-install-and-configure-phpmyadmin)
