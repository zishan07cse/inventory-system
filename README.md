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

Login Page:

![Screenshot 2024-02-28 230839](https://github.com/zishan07cse/inventory-system/assets/71685189/61c0a121-19ce-48e8-a569-71a54dc7d072)

Admin Panel Page:

![Screenshot 2024-02-28 230945](https://github.com/zishan07cse/inventory-system/assets/71685189/4231f9ce-5450-461f-b261-158c22cae14e)

Pos Panel Page:

![Screenshot 2024-02-28 231008](https://github.com/zishan07cse/inventory-system/assets/71685189/47bb90c4-66f0-4ee6-97f8-1e09f6daf56

Customer Page:

![Screenshot 2024-02-28 231043](https://github.com/zishan07cse/inventory-system/assets/71685189/9546a5f9-2f4f-422c-84d8-33b1c3166b80)
