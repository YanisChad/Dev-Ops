
# TP2 Docker

## Question 1
Code ajouté sur le repo

## Question 2
Voir Dockerfile

## Question 3
Pour lancer une image de base de donnée utiliser la commande 
```bash
docker run --name db -e MYSQL_ROOT_PASSWORD=admin -d mysql
```

## Question 4 
Il suffit de décommenter la partie qui permet d'utiliser mysql et de commenter celle qui utilise sqlite dans index.js et de renseigner les bon logs dans db.config.js.
Puis utiliser la commande ```docker compose build```
Ensuite lancer les conteneurs avec ```docker compose up -d```
