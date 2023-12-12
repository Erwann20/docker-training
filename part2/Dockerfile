# Utilisez une image de base Ubuntu
FROM ubuntu:20.04

# Mise à jour des paquets et installation d'une application exemple (optionnel)
RUN apt-get update && \
    apt-get install -y \
    curl

# Définissez le répertoire de travail (optionnel)
WORKDIR /app

# Commande par défaut à exécuter lorsque le conteneur démarre
CMD ["bash"]
