TP SCR - Docker compose pour implémenter une architecture n-tiers (3-tiers) avec Docker:

* Le front-end pourra accéder au mid-tier
* Le mid-tier pourra accéder à la BDD

Pour executer cette application, il faudra simplement taper ```docker-compose up``` (ou ```docker compose up``` suivant la version). Docker va créer alors la base de données [MongoDB](https://www.mongodb.com/) depuis l'image de base [mongo](https://hub.docker.com/_/mongo). L'api utilise [nodejs](https://nodejs.org/) avec [express](http://expressjs.com/) elle devra être construite sur une image [node:alpine](https://hub.docker.com/_/node). Le Front utilise [ReactJS](https://reactjs.org/) et est construit sur une image [node:alpine](https://hub.docker.com/_/node).
