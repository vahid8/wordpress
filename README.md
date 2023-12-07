# wordpress
### step 1
add .env file containg: 
MYSQL_ROOT_PASSWORD=...
MYSQL_DATABASE=wordpress
MYSQL_USER=wordpress
MYSQL_PASSWORD=...
WORDPRESS_DB_HOST=db
WORDPRESS_DB_USER=wordpress
WORDPRESS_DB_PASSWORD=...
WORDPRESS_DB_NAME=wordpress

### step 2
chnage website name in nginx and docker compose (certbot part)

### step 3 check if certificate is mounted:

sudo docker compose exec webserver ls -la /etc/letsencrypt/live
