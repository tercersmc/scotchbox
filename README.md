Scotch Box
==========

Entorno de Desarrollo con Scotch Box

### Requerimientos

- **[VirtualBox][1]** (Creador de maquinas virtuales)
- **[Vagrant][2]** (Crea el entorno virtual dentro de VirtualBox)
- **[Git][4]** (Pone a su disposicion los repositorios de [GitHub][3] en el caso de windows instala git bash)
- **[Scotch Box][5]** (se descargara al levantar el Vagrant)

### Procedmiento

- Descargar eh instalar VirtualBox y **luego** Vagrant en sus ultimas versiones, instalar Git
- Entrar en la shel (git bash en windows) y clonar [este repositorio](https://github.com/tercersmc/SCOTCH-BOX) en la carpeta de su preferencia.
- Ejecutar el comando ```vagrant up```
Luego de un rato su entorno virtual estara en marcha,

- usar http://192.168.33.10/ para entrar a la pagina inicial de su local host

## Comandos importantes

- ```vagrant up``` Levanta el entorno de desarrollo
- ```vagrant halt``` Detiene el entorno de desarrollo
- ```vagrant destroy```Elimina el entorno de desarrollo
- ```vagrant suspend``` Pondra el entorno de desarrollo en estado suspendido
- ```vagrant ssh``` Para entrar el la maquina virtual

## Datos del nuevo entorno

### System Stuff

- Ubuntu 14.04 LTS (Trusty Tahr)
- PHP 5.6
- Ruby 2.2.x
- Vim
- Git
- cURL
- GD and Imagick
- Composer
- Beanstalkd
- Node
- NPM
- Mcrypt

### Database Stuff
- MySQL
- PostgreSQL
- SQLite

### Caching Stuff

- Redis
- Memcache and Memcached

### Node Stuff

- Grunt
- Bower
- Yeoman
- Gulp
- Browsersync
- PM2

### Laravel Stuff

- Laravel Installer
- Laravel Envoy
- Blackfire Profiler

**El Password de Mysql y demas es "root" (sin las comillas) **

Para informacion en detalle verificar la documentacion de cada una de las aplicaciones aqui mensionadas

##  [Vagrant][2]  [virtualBox][1]  [Git][3]  [GitHub][4]  [Scotch Box][5]




[1]:https://www.virtualbox.org/
[2]:https://www.vagrantup.com/
[3]:http://git-scm.com/
[4]:https://github.com/
[5]:box.scotch.io
