1. edit .env configuration and make database name exc: inventaris_sederhana or uptoyou
2. run migration: php artisan migrate
3. run seeder: php artisan db:seed
4. generate APP_KEY: php artisan key:generate
5. clear cache config: php artisan config:cache
6. and then run: php artisan serve

before running above steps, first you must run this if you don't have composer in your local:
run: composer install


note:
1. for regenerate migration:
    php artisan migrate:fresh --seed
