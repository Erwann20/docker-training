1 - À quoi sert Docker ? 

Docker est un outil open source permettant de définir et mettre en place des conteneurs.

Qu'est ce qu'un conteneur ? Une boite qui encapsule une application et ses dépendances, ainsi que les informations de configuration nécessaires pour qu'elle puisse s'exécuter de manière cohérente sur n'importe quel environnement

Plus d'info: https://fr.wikipedia.org/wiki/Docker_(logiciel)

2 - Problème sans Docker

Stack:
- PHP symfony
- DB mongodb
- DB postgres
- Redis

Problème:
- On doit installer tous les outils sur ça machines
- On doit installer les mêmes version qu'en prod
- On doit avoir le même OS avec la même version que la prod

Au final, c'est diffile d'avoir le même environnement que la prod ce qui peut emmener à des bugs surpises.

3 - Avantage de docker

- Isolation d'applications : Docker utilise des conteneurs pour encapsuler des applications et garantir leur isolation par rapport à l'environnement hôte.
- Portabilité : Les conteneurs Docker peuvent s'exécuter de manière cohérente sur n'importe quel système prenant en charge Docker, que ce soit un ordinateur de développement, un serveur de test ou un environnement de production
- Déploiement rapide : Docker facilite le déploiement rapide des applications.
- Gestion des versions : Docker permet de créer des images contenant toutes les dépendances nécessaires à une application.