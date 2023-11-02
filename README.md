### Prerequisites

**Composer**

**Laravel**

### Cloning the repository

```shell
git clone https://github.com/tuanloc288/laravel-api.git
```

### Database set up
1. First you will have to create a database on phpmyadmin (xampp) with whatever name you like
2. Then create an .env file with all the same variable from .env.example
3. Change the value of DB_DATABASE to the db name that you have created  
4. After that run the command below 

```shell
php artisan migrate
```

## You can create dummy data by using this command
```shell
php artisan migrate:fresh --seed
```

### How to run
```shell
php artisan serve
```
