
# TP1 Docker

#### Question 3 
a. J'utilise la commande suivante pour récupérer l'image sur le docker hub
```bash
 docker pull httpd
```

b. Pour vérifier que je dispose bien de l'image en local j'utilise la commande suivante qui liste toutes les images installés localement
```bash
docker image list
```

c. Création d'un dossier html et d'un fichier index.html dedans

d. Je démarre le conteneur avec la commande suivant : -p est utilisé pour spécifier le port et -v la page a servir
```bash 
docker run -p 80:80 -v C:\Users\yanis\Documents\YNOV\B3\DevOps\Docker-TP1\TP_DOCKER_1\html\:/usr/local/apache2/htdocs/ httpd
```