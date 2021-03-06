![alt text](https://raw.githubusercontent.com/jubileedev/ehayes_caffeinetracker/dfd90152ddc06db1c40e0259ffb7bdf21f585095/Screen%20Shot%202019-11-24%20at%209.32.19%20PM.png)


## About Caffeine Tracker

Caffeine Tracker is a simple tool for users to track their caffeine intake each day. 

## Features

- Select drinks along w/ amount of servings to see your new total (TOTAL CAFFEINE ALLOWANCE)
- Provides feedback on how much of that drink you can still have to stay under 500 mg.
- Track History of previous entered drinks
- Add new drinks to the database 
- Remove previous entries in your drink history


## Initial Setup

Step 1: Clone the repo

Step 2: cd into root of project directory

> cd *projectName*

Step 3: run NPM install from root directory

> npm install 

Step 4: run Composer to load dependencies from root directory

> composer install

Step 5: Rename .env_example to *.env* and put your db credentials you want this project to use

Step 6: Migrate tables to database

> php artisan migrate

Step 7: A *Drinks DB Seeder* was provided. If you wish to pre-load the database with 5 unique drinks run the following command

> php artisan db:seed

Step 8: run in browser

> php artisan serve

Step 9: Enjoy


