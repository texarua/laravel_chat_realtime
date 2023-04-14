1 --- cd to root project 
2 --- clone laradock -> cd laradock
3 --- docker-compose up -d nginx php-fpm workspace phpmyadmin mysql redis
4 --- exec workspace docker by id 
    -> php artisan migrate
    -> php artisan db:seed
    -> php artisan queue:listen
