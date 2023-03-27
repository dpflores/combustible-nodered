# Nodered en docker 

Este archivo crea un contenedor de nodered versión 2.2.3-12 con una base de datos mariadb. Ser ecomiendo usar phpmyadmin para que puedan visualizar la base de datos. Para ver la interfaz de nodered, ingresar la ip del dispositivo con el puerto 1880 en el url.
 
 Esto es para arm, v7 y funciona idealmente en el Axotec.

 Para que el folder de data de nodered se pueda utilizar, ejecutar 

 ```
 sudo chown -R 1000:1000 path/to/your/node-red/data
 sudo chown -R 1000:1000 nodered-data
 ```