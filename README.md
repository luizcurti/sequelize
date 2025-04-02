# Sequelize Node.js Study
A study project using Node.js with Sequelize.

## Features
Database connection using Sequelize ORM

Migrations and models for structured data management

Environment configuration for database credentials

## Installation & Setup

Clone the repository:
* git clone https://github.com/luizcurti/sequelize.git
* cd sequelize

Configure database credentials in /src/config/database.js.

1. Install dependencies:
* yarn

2. Create the database:
* yarn sequelize db:create

3. Run migrations:
* yarn sequelize db:migrate

4. Start the server:
* yarn dev

Import Insomnia_2019-10-16.json into Insomnia for API testing.