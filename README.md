Beston Login Test Demo
========

The project is a web application that allows users to login and register using their credentials securely. It showcases the integration of Laravel 8 as the backend API and ReactJS for the frontend user interface. 

To get started, simply dowload this repo.

## Notice
 - In 'forget password' function, it will send a 4 digital code from a gmail to user's email so that it can allow to reset password. However, now it is not avaliable. Because google has made some changes to its security settings. 
 - But you can still find the 4 digital code in database, the table is called "password_resets"

## Table of Contents

 * [Getting Started](#getting-started)
 * [Frontend Technology Stack](#frontend-technology-stack)
 * [Backend Technology Stack](#backend-technology-stack)
 * [Frontend Run](#frontend-run)
 * [Backend Run](#backend-run)
 * [Author](#author)
 * [Issues?](#issues)
 * [License](#license)
 * [Requirments](#requirments)


## Getting Started

Clone from Github 
```
git clone https://github.com/lihongtao0406/beston_login_test.git
```

## Frontend Technology Stack

 - [Material UI V5](https://material-ui.com/)
 - Built with React Hooks API
 - Redux & React Context API for State Management
 - React Router for Navigation Routing
 - Support of react-script
 - Code Splitting
 - CSS-in-JS where CSS is composed using JavaScript instead of defined in external files

## Backend Technology Stack

 - Laravel8 (https://laravel.com/docs/8.x/installation) & Laravel Passport(https://laravel.com/docs/8.x/passport)
 - XAMPP 
 - RESTful Api
 - Mysql


## Database Setting
- Make sure XAMPP is running
- Create a New Database(Optional)
- Choose 'heroku_7a2e3a7210f9a2f.sql' to Import


## Database Configure

To connect your Laravel 8 project to Mysql, you need to set up the following database configuration in the `.env` file:
```dotnev
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_PASSWORD=your_database_pwd
```
## Frontend Run

Open terminal and direct to frontend directory to input

```
yarn install
```

After that to start frontend serve

```
yarn start
```
## Backend Run

Open terminal and direct to backend directory to input

```
composer install
```
After install all package, start the backend serve

```
php artisan serve
```

After that backend api will be successfully started

## Author

This repo is compiled by Tao

## Issues

Please generate a [Github issue](https://github.com/lihongtao0406/beston_login_test/issues) if you found a bug in any version. I am trying to be responsive to resolve the issue.

## License

 - Licensed cover under [MIT](https://github.com/codedthemes/datta-able-bootstrap-dashboard/blob/master/LICENSE)
 
## Requirments

 - mysql version libmysql 
 - mysqlnd 8.0.13 
 - php version 8.0.13
 - laravel version 8.16.1
 - NodeJS version 16.8
 - React version 17.0.1
 - Material-ui version v5

## Third party API
 - [Google OAuth 2.0](https://developers.google.com/identity/protocols/oauth2)



