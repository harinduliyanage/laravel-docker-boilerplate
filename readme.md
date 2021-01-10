
To up and running boilerplate execute

docker-compose up -d

to integrate with laravel project

1. cd application && rm public
2. copy or initialize laravel project inside application project
3. docker-compose exec php php /var/www/html artisan migrate
