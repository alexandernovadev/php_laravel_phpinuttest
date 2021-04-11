<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>


## Crear un modelo

php artisan make:model Post -fm

## Crear un test
php artisan make:test Http/Controllers/Api/PostControllerTest

# Run Test

vendor/bin/phpunit   

# Only a ONe methods
vendor/bin/phpunit  --filter test_update 


# Make test unit
 php artisan make:test UserTest --unit                        

# Make controller only api
php artisan make:controller Api/PostController --api --model=Post

# Make sqli database and configure
1 crear database.sqlite en la carpeta database
2 'database' => env(database_path('database.sqlite')), en config database 

