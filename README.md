<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

# laravel 9 CRUD

Basic CRUD , AUTH system and Role mangment system Operation with Laravel 9 and bootstrap 4


## What's this repo about

Simply, it's a basic create, read, update and delete operation with Laravel 9 and Bootstrap 4. 

## Features

- Role management (list,create,delete,edit)

- User management (list,create,delete,edit)

- Account settings 

## Tech

- BOOTSRAP 4

- LARAVEL 9

- PHP8


## Requirements

- PHP >= 8.0.0

- PDO PHP Extension

- Mysql 

- Composer >= 2.2.3


# Installation
Just clone the project to anywhere in your computer.
```bash
git clone https://github.com/halimhmairi/laravel-9-roles-and-crud.git
``` 

Then do a composer install

```bash
composer install
``` 

Then create a environment file using this command-
```bash
cp .env.example .env
``` 
Then edit .env file with appropriate credential for your database server. Just edit these two parameter(```DB_USERNAME``` , ```DB_PASSWORD``` ).

and

```bash
php artisan db:seed 
``` 
```bash 
php artisan migrate
``` 
Now you are done.

```bash
php artisan serve
``` 
and open the project on the browser.
## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
