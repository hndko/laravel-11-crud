# Laravel 11 - CRUD

Belajar CRUD Laravel 11 Beserta File Upload

## Installation

```bash
  git clone https://github.com/hndko/laravel-11-crud.git
  composer Install
  cp .env.example .env
  php artisan key:generate
  php artisan storage:link  
```

## Documentation

Change .env database

```bash
DB_CONNECTION=sqlite
# DB_HOST=127.0.0.1
# DB_PORT=3306
# DB_DATABASE=laravel
# DB_USERNAME=root
# DB_PASSWORD=
```

To

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_laravel11
DB_USERNAME=root
DB_PASSWORD=
```

And Then

```bash
php artisan migrate
php artisan serve
```

## Support

For support, email hd.doko22@gmail.com or join our KodeKreatif channel.
