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
