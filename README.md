# m-uang

m-uang is a personal bookkeeping web application, built with Laravel 5.

## Objective
Easy bookkeeping for personal income and spending (amount of money).

## Concept

To aquire our objective, we need this features on the application:

- Admin can access all fiture.
- Admin can add, edit and delete sumber.
- Admin can add, edit and delete pemasukan details.
- Admin can add, edit and delete pengeluaran datails.
- Admin can view all sumber, pemasukan, and pengeluaran on dashboard.
- etc.

Those are basic concept of the personal bookkeeping service.

## Getting Started
This application can be installed on local server and online server with these specifications :

#### Server Requirements
1. PHP 7.2 (and meet [Laravel 5.x server requirements](https://laravel.com/docs/6.x#server-requirements)),
2. MySQL or MariaDB database,
3. SQlite (for automated testing).

#### Installation Steps

1. `$ cd m-uang`
2. `$ composer install`
3. `$ cp .env.example .env`
4. `$ php artisan key:generate`
5. Create new MySQL database for this application  
(with simple command: `$ mysqladmin -urootuser -p create dompet_db`)
6. Set database credentials on `.env` file
7. `$ php artisan migrate`
8. `$ php artisan serve`
9. set url to : setup, example : localhost/setup, to setup admin login
10. Default Login : email: admin@localhost.com | password : admin

## Contributing

If you are considering to contribute to this repo. It is really nice.

1. Submit Issue if you found any errors or bugs or if you want to propose new feature.
2. Pull Request for bugfix, typo on labels, or new feature.

## Screenshots

#### Dashboard

![Managemen Keuangan | m-uang](public/screenshot/Dashboard.png)

#### Sumber Pemasukan

![Managemen Keuangan | m-uang](public/screenshot/Sumber.png)

#### Pemasukan

![Managemen Keuangan | m-uang](public/screenshot/Pemasukan.png)

#### Pengeluaran

![Managemen Keuangan | m-uang](public/screenshot/Pengeluaran.png)

## License

m-uang is a free and open-sourced software under [MIT License](LICENSE).