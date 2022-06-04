# lancer cette commande pour obtenir un nginx de base

sudo docker run --name docker-nginx -p 80:80 -d -v .:/usr/share/nginx/html  nginx
