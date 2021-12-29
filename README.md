# store_app
 Inventory  and Point of sale system for stores
	## POS and Inventory app using laravel and Vue js

## get it up and running.

After you clone this project, do the following:

```bash
# go into the project
cd / store_app_laravel_vue

# create a .env file
cp .env.example .env
# install composer dependencies
composer update
# install npm dependencies
npm install
# generate a key for your application
php artisan key:generate
# create a local MySQL database (make sure you have MySQL up and running)
mysql -u root
> create database chat_db;
> exit;
# add the database connection config to your .env file
DB_CONNECTION=mysql
DB_DATABASE=inventory
DB_USERNAME=root
DB_PASSWORD=
# run the migration files to generate the schema
php artisan migrate

# seed your databse with some users and messages
php artisan db:seed
# run webpack and watch for changes
npm run watch
```



Good Luck :)
