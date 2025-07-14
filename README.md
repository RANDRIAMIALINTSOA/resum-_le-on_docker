# resum-_le-on_docker
## Définition
Docker est une plateforme permettant de automatiser le déploiement, la gestion et l'exécution d'applications dans des conteneurs. Les conteneurs sont des environnements isolés et légers qui contiennent tout le nécessaire pour faire fonctionner une application : code, runtime, bibliothèques, etc.
## Concepts clés
-Image Docker : 
modèle immuable contenant tout ce dont une application a besoin pour fonctionner.
-Conteneur : i
nstance en exécution d'une image Docker.
-Dockerfile : 
fichier dans lequel vous écrivez les instructions pour construire une image Docker.
-Registry : 
lieu de stockage et de distribution d'images Docker, comme Docker Hub.

~~~
docker run -d -p 8080:80 --name mon_conteneur nom_image
~~~

