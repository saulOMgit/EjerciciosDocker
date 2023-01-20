# Ejercicios Docker 2 - Imagenes

1. Descarga las siguientes imágenes: ubuntu:18.04, httpd, tomcat:9.0.39-jdk11,jenkins/jenkins:lts, php:7.4-apache.

![](./img/1_1.png)
![](img/1_3.png)
![](img/1_4.png)

2. Muestras las imágenes que tienes descargadas.

![](img/1_2.png)

3. Crea un contenedor demonio con la imagen php:7.4-apache.

![](img/3.png)

4. Comprueba el tamaño del contenedor en el disco duro.

Lo he intentado tambien con inspect -s pero no me funciona
![](img/4.png)

5. Con la instrucción docker cp podemos copiar ficheros a o desde un contenedor. Puedes encontrar información es esta <a href="https://docs.docker.com/engine/reference/commandline/cp/" target="_blank">página</a>. Crea un fichero en tu ordenador, con el siguientecontenido:Copia un fichero info.php al directorio /var/www/html del contenedor con docker cp.

![](img/5.png)

6. Vuelve a comprobar el espacio ocupado por el contenedor.

![](img/6.png)

7. Accede al fichero info.php desde un navegador web.

![](img/7.png)