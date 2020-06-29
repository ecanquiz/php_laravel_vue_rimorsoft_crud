# php_laravel_vue_rimorsoft_crud
Php Laravel Vue Rimorsoft Crud

Information Source:

https://rimorsoft.com/tecnologias-webpack-y-laravel-mix

Lesson 1 - Webpack and Laravel Mix Technologies

$ composer create-project --prefer-dist laravel/laravel php_laravel_vue_rimorsoft_crud

In webpack.mix.js file:

mix.scripts([

        'resources/assets/js/vue.js',

        'resources/assets/js/axios.js',

        'resources/assets/js/app.js'

    ], 'public/js/app.js');

To make use of Laravel Mix we must first install it, to use the npm commands we must have installed Node.js since it would become a kind of composer for the FrontEnd. So to install Laravel Mix we write the following command to the console: sudo npm install.

Inside the resources/assets folder of our project, we are going to place locally the script files necessary to work, these files would be vue.js, axios.js and a file for our own javascript code with the name of app.js. Using laravel Mix we will group these 3 files to make one and replace the app.js file that comes by default located in the following path public / js / app.js.

$ sudo npm install

Lesson 2 - Controllers, Routes, Views, Database for the CRUD

php artisan make:model Task -m

php artisan config:clear

php artisan migrate:refresh

php artisan make:controller TaskController --resource

php artisan route:list

Lesson 3 - Connection API

$ php artisan make:seeder TasksTableSeeder

$ php artisan migrate:refresh --seed

Lesson 4 - Data list

php artisan route:list

npm run dev

Lesson 5 - Delete records

$ php artisan migrate:refresh --seed

$ npm run dev

$ php artisan route:list

Lesson 6 - TOASTR notifications

$ npm run dev


















