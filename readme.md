# Laravel and AngularJS CMS

CMS built on Laravel, AngularJS and Material Design

## Features

- Users/User Roles, Posts, Gallery, Profile  CRUD
- John papa Angular style
- Material Design
- Image Manipulation
- Sass

## Getting Started

Clone Repo

````
git clone https://github.com/DimitriMikadze/laravel-angular-cms.git
````

Create Database

Cd project and run composer update and npm install

````
cd laravel-angular-cms
composer update
npm install
````

Add .env file to root directory.

Example:

````
see .env.example file
````

Migrate tables

````
php artisan migrate
````

Seed tables

````
php artisan db:seed
````

Start Server

````
php artisan serve
````

## gulp

watch changes

````
gulp watch
````

## gulp minify stylesheets and scripts

````
gulp --production
````

## Angular

you can find angular files in

````
resources/assets/js/admin/app
````

output files

````
public/admin/js
````

## Sass

Sass files

````
resources/assets/sass/admin
````

output files

````
public/admin/css
````

## Contributing

contributions are more than welcome!

## License

See license.txt