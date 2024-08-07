## Laravel 10.10 HMVC Project Setup
-- https://laravelmodules.com/docs/v10/introduction

## Installation Guide 

- Clone this project 
```
    run  composer update

```
- Server start
```
    php artisan serve

```

- Create Module:
```
php artisan module:make posts // all api and web 
php artisan module:make posts -p // --plain
php artisan module:make Blog --api  // --api
php artisan module:make Blog -d // --disabled

```


- create Module Model :

   - php artisan module:make-model <ModelName> <option> <ModuleName>
    Example : model with migration file create
    ```
     php artisan module:make-model Post -m Blog

    ```
