1 - Qu'est-ce qu'une image docker ?

ça va être un fichier qui va comprendre certaines instructions permettant d'encapsuler tout ce qu'il faut pour faire fonctionner une application.

Pleins d'images dispos: https://hub.docker.com/

2 - Comment on crée sa propre image docker ?

Il suffit de créer un fichier Dockerfile.

Pour créer son image une fois le docker file créer:
docker build -t demo .

Pour lancer l'image dans un conteneur:
docker run -it demo bash

guide / bonne pratique: https://docs.docker.com/develop/develop-images/dockerfile_best-practices/

https://github.com/docker-library/redis/blob/master/Dockerfile.template