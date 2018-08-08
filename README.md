# P1NodeLoginMap1
Primer proyecto de la materia Topicos Especiales en Telemática
Objetivo:

Desarrollar una aplicación web tipo IoT haciendo uso de frameworks web modernos y utilizando buenas prácticas DevOps

Descargar Codigo:
``` 
https://github.com/stiag0/Proyecto1Telematica.git
```

Ejecucion de la aplicacion

Es necesario tener instalado en la máquina los servicios de Docker y Docker-compose

Instalar docker en ubuntu
```
  $ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  $ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu$(lsb_release -cs) stable"
  $ sudo apt-get update
  $ sudo apt-get install docker-ce
```
Una vez descargado el repositorio, se realizarán los siguientes comandos:
```
$ sudo docker-compose build

$ sudo docker-compose up
```
En caso de querer utilizarlo de manera local:
```
  $ emacs index.js
  //cambiar linea 18 por var 
  promise = mongoose.connect('mongodb://server-login/loginGPS', {
```
Esto montará la aplicacion en el servidor o en el Localhost
Se puede acceder a la aplicación a través del siguiente link: https://dsalasz26.dis.eafit.edu.co
