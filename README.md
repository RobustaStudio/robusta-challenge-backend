# DevOps Backend Component

This application is built using Laravel framework which is based on PHP. To get the application running you need to ensure the following:

- Install MySQL Database
- Create a database
- Run `cp .env.example .env`
- add `DB_DATABASE=database_name_created` to the created `.env` file.
- Run the following commands
    ```
    composer install
    
    php artisan key:generate

    php artisan migrate
    ```
- use TablePlus app to fill table with users data
- run php artisan serve to have the application up and running
