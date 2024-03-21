# Simple Python project



## Description
Ceci est une application Flask simple qui affiche une page d'accueil avec le contenu du fichier `index.html`.
Cette application est hébergé dans un dockerhub **tukaari/flask-repository**.
Il y a également un conteneur prometheus et un conteneur grafana pour le monitoring de l'application.


## Installation
Faire `git clone https://gitlab.com/simple-python-project/simple-python-project.git` pour installer le projet.
Faire `cd flask_docker` puis `docker-compose up -d`.


## Explication
Le fichier **prometheus.yml** sert à prendre les metrics du **service web** au **port 5000**.
Le fichier **datasource.yml** sert à mettre le **service promotheus** **port 9090** en tant que source de donnée.


## Accessibilité
Vous aurez **l'application** sur le port **5000**, **prometheus** sur le port **9090** et **grafana** sur le port **3000**.