web: vendor/bin/heroku-php-nginx -C nginx_app.conf public/
release: composer update && php artisan cache:clear && php artisan config:cache && php artisan route:cache && php artisan view:cache
