#Archivco donde especificamos la instalación de librerías y configuraciones a la hora de crear contenedores personalizados
#partimos de una imagen de Docker con Apache instalado
#FROM ubuntu + instalación personal de apache
FROM httpd:2.4
#debemos consultar el docker hub (imagen) para ver variables de entorno 
#directorios de trabajo etc etc 
#directorio de trabajo dentro del contenedor
WORKDIR /usr/local/apache2/httpdocs
COPY ../src .
EXPOSE 80
