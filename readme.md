## Building Ecommerce Using Laravel v5.8

### 1. Creating the project

    > - composer create-project laravel/laravel Lara_GeniusCart58 "5.8.*"
    > - create new repository
    > - test the new project :-)
    > - create local repository
    > - git commit -m "1. Initial commit: craete the project"
    > - push repo to github

### 2. Modify the app to default root without /public

    > - renamed:    public/.htaccess -> .htaccess
    > - renamed:    public/index.php -> index.php
    > - modified:   readme.md
    > - modified:   server.php
    > - test it out
    > - now the default root BEFORE: http://127.0.0.1:8000/public
    > - now the default root AFTER: http://127.0.0.1:8000/
    > - git commit -m "2. Modify the app to default root without /public"


### 3. Create user auth

    > - 1. create database
    > - 2. add db credentials to .env
    > - 3. migrate
    > - 4. create user auth =>  php artisan make:auth
    > - default files created...
        > - new file:   app/Http/Controllers/HomeController.php
        > - modified:   readme.md
        > - new file:   resources/views/auth/login.blade.php
        > - new file:   resources/views/auth/passwords/email.blade.php
        > - new file:   resources/views/auth/passwords/reset.blade.php
        > - new file:   resources/views/auth/register.blade.php
        > - new file:   resources/views/auth/verify.blade.php
        > - new file:   resources/views/home.blade.php
        > - new file:   resources/views/layouts/app.blade.php
        > - modified:   routes/web.php
    > - git commit -m "3. Create user auth"
