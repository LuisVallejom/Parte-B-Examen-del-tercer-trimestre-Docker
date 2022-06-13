# Parte-B-Examen-del-tercer-trimestre-Docker


## Ejemplo 2.1
### Ejemplo 1

#### Iniciamos sesion del docker hub mediante la consola/terminal de Ubuntu, y Hacemos login del Docker con la fecha y dia de hoy.

![Captura de pantalla login ](https://user-images.githubusercontent.com/82807688/173307963-82145d33-cbdd-420b-8b60-758334d702a3.png)

#### A continuación descargarmos una imagen, que en este caso será ubuntu.

![Captura de pantalla 2 descargar imagen ](https://user-images.githubusercontent.com/82807688/173308155-3c065e74-60e7-43d5-9547-669b9bbeb1f6.png)

#### Y a continuación creamos un contenedor con un `docker run -it`.

![Captura de pantalla 3 crear repositorio](https://user-images.githubusercontent.com/82807688/173309388-dd581063-7f88-4dd4-a6b6-0338ac2cd8ab.png)


### Ejemplo 2.

#### Creamos un contenedor y después listamos el contenido de la caarpeta
![Captura de pantalla ejemplo 2 ubuntu](https://user-images.githubusercontent.com/82807688/173309727-1f0a8709-cc79-492e-9169-35aeda812071.png)

### Ejemplo 3

#### Creamos un contenedor de httpd
![Captura de pantalla ejemplo 3 descargada ](https://user-images.githubusercontent.com/82807688/173309885-ac25e736-4422-4d9d-a94c-a3f1b48f3dba.png)

### Ejemplo 4.
#### Crear un contenedor de debian 9 y mostrar el contenido de una carpeta establecida con el parámetro -w.
![Captura de pantalla ejemplo 4 crear debian](https://user-images.githubusercontent.com/82807688/173310077-43b44c0c-44f7-4efa-970d-89380004869e.png)

#### Después mostramos los contenedores en ejecución con `docker ps`.
![Captura de pantalla mostrar archivos de debian](https://user-images.githubusercontent.com/82807688/173310710-06cc6ade-d1fd-461a-b291-e7a1a1a59743.png)

#### Mostrar todos los contenedores creados ya estén en ejecución o parados.

![Captura de pantalla ejemplo 4 mostrar los contenedores creados ya en ejecucion o parados](https://user-images.githubusercontent.com/82807688/173310134-0685096d-f647-4104-85ae-899fe655a0ef.png)


## 6.2.2 Ejemplos de ficheros Dockerfile.

### Descargar tomcat.

![Captura de pantalla tomcat descargada 1](https://user-images.githubusercontent.com/82807688/173312165-e108184f-1f5b-4487-9487-1f4f7a77da1c.png)

### Después hacemos una instalaciones básicas. 
![Captura de pantalla installing basic tools](https://user-images.githubusercontent.com/82807688/173312621-ec80e066-5820-4929-b4df-88cb87b30a85.png)


### Segundo, una vez ya hecho la instalación básica, seguimos con estos comandos `mv /usr/local/tomcat/webapps.dist/* /usr/local/tomcat/webapps` y `rm -rf /usr/local/tomcat/webapps.dist`.
![Captura de pantalla mv](https://user-images.githubusercontent.com/82807688/173315274-50bed865-c20d-4d14-bc05-c631844cebca.png)
![Captura de pantalla rm](https://user-images.githubusercontent.com/82807688/173315290-cb195b20-f1bc-4624-8f5b-ac5b694cd2b9.png)



### Tercero copiamos el tomcat a un contenedor.
![Captura de pantalla Copiar el tomcat a un contenedor](https://user-images.githubusercontent.com/82807688/173313916-dcd90e6c-840f-4d2b-aacd-9f3b3fbbeec5.png)
![Captura de pantalla mycontest manager](https://user-images.githubusercontent.com/82807688/173315618-52734f34-38b1-4fd1-874d-2ea4c0ac05e4.png)

### Cuarto modificamos desde todas las apps.

![Captura de pantalla final](https://user-images.githubusercontent.com/82807688/173315662-b84b68d1-a207-4509-b100-1fac7f3dfa08.png)










