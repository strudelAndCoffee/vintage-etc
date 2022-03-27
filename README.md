# Vintage, Etc.

![License badge](https://img.shields.io/badge/License-ISC-green)
![Code of Conduct badge](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)

## Description

This project demonstrates the server/database connection for an E-Commerce shopping site. The server runs on Node.JS and Express, and establishes RESTful API calls to a SQL database through MySQL and Sequelize. The repo does dot include any front end for user interactions, so testing the functionality requires an API testing platform such as Insomnia. The project also requires MySQL to be installed and having an account to access databases using MySQL shell.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Tests](#tests)
* [Questions](#questions)
* [Contributing](#contributing)
* [License](#license)

## Installation

From the root directory of the repo:

In the terminal, enter this command to install dependencies: `npm install`

(To verify that everything is installed, check the "package-lock.json" in the root directory of the repo.)

Then, in MySQL shell, enter this command to connect to the database: `source db/schema.sql;`

## Tests

From the terminal, enter this command to seed the database with test data: `npm run seed`

Enter this command to run the application: `npm start`

## Usage

You may watch a walk-through tutorial video here:

After installing the dependencies, and setting up/seeding the database...

![]

Connect to the server by typing `npm start` in the terminal.

![]

Through the API routes, you can make GET, POST, PUT, and DELETE calls to the database. Since the repo is not deployed, you must use an API testing platform, such as Insomnia.

![]

## Questions

For additional questions, you may reach me via email: strudelandcoffee@gmail.com 

View my GitHub profile: [strudelAndCoffee](https://github.com/strudelAndCoffee)

## Contributing

Please review the Contributer Covenant [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.txt)

## License

This project is licensed under [ISC](https://choosealicense.com/licenses/isc)
