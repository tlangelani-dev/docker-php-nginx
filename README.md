## Lets setup Docker with Nginx, PHP and MySQL shall we

# build the containers
`docker-compose build`
# fire them up
`docker-compose up -d`
# stop the containers
`docker-compose down`

- To run laravel migrate: `docker-compose exec php php /var/www/html/artisan migrate`
