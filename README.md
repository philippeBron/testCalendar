# Tests d'utilisation d'un calendrier
L'objectif est d'afficher sur un calendrier la disponibilité de ressources et permettre la réservation dans la limite de capacité de chaque ressource.

## test et deploiement
Les tests peuvent être réalisés en utilisant un conteneur apache/php avec la commande suivante
```
  docker run -d -p 80:80 --name candilib -v "$PWD/public-html":/var/www/html php:7.0-apache
```
