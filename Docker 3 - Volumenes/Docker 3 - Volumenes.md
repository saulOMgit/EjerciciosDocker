# Ejercicios Docker Volumenes

## Vamos a trabajar con volúmenes docker:

### 1. Crea un volumen docker que se llame miweb.

![](img/volumen1.png)

### 2. Crea un contenedor desde la imagen php:7.4-apache donde montes en el directorio/var/www/html (que sabemos que es el DocumentRoot del servidor que nos ofrece esaimagen) el volumen docker que has creado.

![](img/volumen2.png)

### 3. Utiliza el comando docker cp para copiar un fichero index.html en el directorio/var/www/html.

![](img/volumen3_1.png)
![](img/volumen3_2.png)

### 4. Accede al contenedor desde el navegador para ver la información ofrecida por el fichero index.html.

![](img/volumen4.png)

### 5. Borra el contenedor

![](img/volumen5.png)

### 6. Crea un nuevo contenedor y monta el mismo volumen como en el ejercicio anterior.

![](img/volumen6_1.png)


### 7. Accede al contenedor desde el navegador para ver la información ofrecida por el fichero index.html. ¿Seguía existiendo ese fichero?

Sigue existiendo (Captura anterior)

## Vamos a trabajar con bind mount:

### 1. Crea un directorio en tu host y dentro crea un fichero index.html.

![](img/bind1.png)

### 2. Crea un contenedor desde la imagen php:7.4-apache donde montes en el directorio/var/www/html el directorio que has creado por medio de bind mount.

![](img/bind2.png)

### 3. Accede al contenedor desde el navegador para ver la información ofrecida por el fichero index.html.

![](img/bind3.png)


### 4. Modifica el contenido del fichero index.html en tu host y comprueba que al refrescar la página ofrecida por el contenedor, el contenido ha cambiado.

![](img/bind4_1.png)
![](img/bind4_2.png)

### 5. Borra el contenedor

![](img/bind5.png)
![](img/bind5_2.png)

### 6. Crea un nuevo contenedor y monta el mismo directorio como en el ejercicio anterior.

![](img/bind6.png)

### 7. Accede al contenedor desde el navegador para ver la información ofrecida por el ficheroindex.html. ¿Se sigue viendo el mismo contenido?

Lo seguiriamos viendo

![](img/bind7.png)