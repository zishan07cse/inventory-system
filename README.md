## ✨ Inventory Management System

Inventory Management System with Laravel 10 and MySql.

    $ git clone https://github.com/zishan07cse/inventory-system.git
    ```
1. **Setup**
    ```bash
    # Go into the repository
    $ cd inventory-management-system

    $ composer install

    Rename or copy the `.env.example` file to `.env`
 
    # Generate app key
    $ php artisan key:generate
    Setup your database credentials in your `.env` file.
    $ php artisan:migrate:fresh --seed

    $ php artisan storage:link
    $ php artisan serve
    Try login with username: `admin` and password: `password`
