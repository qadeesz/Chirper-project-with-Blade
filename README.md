<!-- php artisan down --secret="youts-screat-key" -->
<!-- https://example.com/1630542a-246b-4b66-afa1-dd72a4c43515 // up again -->



# Laravel Practice project

### PHP v8.1.9
### Laravel v10.0

```
git clone https://github.com/qadeesz/Chirper-project-with-Blade.git
cd Chirper-project-with-Blade
```

## Make database file and connect in .env
```
$ touch database/db.sqlite

-- update in .env
DB_CONNECTION=sqlite
```

## install composer dependancies
```
composer update
composer require laravel/breeze --dev
php artisan breeze:install blade
php artisan migrate
```

## install client side dependancies
```
npm install
npm run build
```

## run project
```
php artisan serve
```
Server running on [http://127.0.0.1:8000].


[Refrance Project Link](https://bootcamp.laravel.com/blade/installation)