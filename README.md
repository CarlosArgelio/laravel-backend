# Development

docker-compose --env-file ./src/.env up -d

docker-compose --env-file ./src/.env exec php php /var/www/html/artisan

docker-compose --env-file ./src/.env exec php php /var/www/html/artisan migrate

sudo chown -R