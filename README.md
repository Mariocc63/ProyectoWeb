# FRONTEND, BACKEND, DOCKER

aplicación web que utiliza una API para hacer CRUD en una base de datos no relacional (Mongodb), para posteriormente subirse en la nube, Azure en este caso, después de generar imagenes docker. La página está basada en una lista de animes que el usuario puede manipular.
Las imagenes de docker son para Mongo, Frontend y Backend


## FRONTEND

-Se utilizó React js

-Axios para la conexión con el backend

-ngixn

-No utiliza bootstrap y ningún otro framework


## BACKEND

-Se utilizó Express js

-Conexión con Mongo con mongoose


## DOCKER

-Creación de docker-compose.yml

-Dockerfile para backend y frontend

-Construcción de las imagenes


## NUBE (AZURE)

-Creación de un Register container, en ellos se almacenas las imagenes de Mongo, Backend y Frontend

-Login para pushear imagenes de docker en el Register container (Terminal)

-Se tagea la imagen y se sube (docker push) al Register container

-Utiliza direccionamiento por ip

-No tiene una DNS que permita redireccionar la ip

###### link de la aplicación: http://40.83.212.62/


