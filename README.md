# Vintage, Etc.

![ISC License badge](https://img.shields.io/badge/License-ISC-green)

## Description

This project demonstrates the server/database connection for an E-Commerce shopping site. The server runs on Node.JS and Express, and establishes RESTful API calls to a SQL database through MySQL and Sequelize. The repo does dot include any front end for user interactions, so testing the functionality requires an API testing platform such as Insomnia. The project also requires MySQL to be installed with an account to access databases using MySQL shell.

## Table of Contents

* [Installation](#installation)
* [Tests](#tests)
* [Usage](#usage)
* [Questions](#questions)
* [License](#license)

## Installation

From the root directory of the repo...

In the terminal, enter this command to install dependencies: `npm install`

(To verify that everything is installed, check that the "package-lock.json" file exists in the root directory of the repo.)

Then, log into MySQL shell, and enter this command to connect to the database: `source db/schema.sql;`

## Tests

First, you must add your MySQL username and password to the ".env" file. You can find this file in the root directory of the repo.

Then from the terminal, enter this command to seed the database with test data: `npm run seed`

Enter this command to run the application: `npm start`

## Usage

You can watch a full walk-through tutorial video here:

[Walk-Through Video](https://drive.google.com/file/d/1PWM67MmnLHGFJ_JD7rQB9lzRvP95ipjg/view?usp=sharing)

After installing the dependencies, and setting up/seeding the database...

![Running MySQL commands in the command terminal](https://github.com/strudelAndCoffee/vintage-etc/blob/main/assets/images/demo-screencap-1.png)
![Running the seed database command in Git Bash](https://github.com/strudelAndCoffee/vintage-etc/blob/main/assets/images/demo-screencap-2.png)

Connect to the server by typing `npm start` in the terminal.

![Connecting to the server in Git Bash](https://github.com/strudelAndCoffee/vintage-etc/blob/main/assets/images/demo-screencap-3.png)

Through the API routes, you can make GET, POST, PUT, and DELETE calls to the database. Since the repo is not deployed, you must use an API testing platform, such as Insomnia.

Try the following API routes:

`api/categories`
`api/products`
`api/tags`

Add `/` and a number ID to the end of the url to view single items.

Try GET, POST, PUT, and DELETE request calls on all routes!

![Making a GET call to the API in Insomnia](https://github.com/strudelAndCoffee/vintage-etc/blob/main/assets/images/demo-screencap-4.png)
![Making a POST cal to the API in Insomnia](https://github.com/strudelAndCoffee/vintage-etc/blob/main/assets/images/demo-screencap-5.png)

## Questions

For additional questions, you may reach me via email: strudelandcoffee@gmail.com 

View my GitHub profile: [strudelAndCoffee](https://github.com/strudelAndCoffee)

## License

This project is licensed under [ISC](https://choosealicense.com/licenses/isc)
