
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

## Question 5
Voir docker-compose.yml et question 4

## Question 6
Je crois que c'est bon mais pas sur, en fait c'est bon

## Question 7
Créer un fichier .env et renseigner les valeurs dedans tels que le mot de passe et le nom d'utilisateur de la DB
Modifier le fichier docker-compose (voir docker-compose)

## Question 8
Pour isoler les deux conteneurs et les mettre dans un même réseau a part, il faut créer un network et les mettre les deux dans réseau crée. (voir docker-compose)