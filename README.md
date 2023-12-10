##  Inventory Management System
Inventory Management System with Laravel 10 and MySql.

##  Features
- POS
- Orders
  - Pending Orders
  - Complete Orders
  - Pending Due
- Purchases
  - All Purchases
  - Approval Purchases
  - Purchase Report
- Products
- Customers
- Suppliers

## How to Use :

#### Downloading composer package and dumping
~~~bash
composer install
~~~

### Copy code from `.env.example` to `.env` file
~~~bash
cp .env.example .env
~~~

#### Configure project
~~~bash
php artisan cache:clear
~~~
~~~bash
php artisan config:cache
~~~
~~~bash
php artisan key:generate
~~~


#### NPM Package
~~~npm
npm install
npm run dev
~~~

### Create a database name and change credential in `.env` file

### migrate and seed database
~~~bash
php artisan migrate --seed
~~~


### Composer load now
~~~bash
composer dump-autoload
~~~


### Serving laravel project
~~~bash
php artisan serve
~~~

