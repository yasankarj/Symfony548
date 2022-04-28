# Symfony548
## This project is to explore new features provided by Symfony 5.4.8.

Symfony is one of the most established PHP frameworks available in the market. It gets improved version by version. This project set up is to achieve following goals.

- Explore new features provided by Symfony 5.4.8
- Try out lates MySQL version features
- Support given on VueJS plugin compatibility


## Installation Steps
> Installing PHP, Apache, MySQL, are prerequisites.

- Create an app => symfony new uom_workshop --full
- Run the server => symfony server:start
- Configure the parameters in .env file
- Create the database => php bin/console doctrine:database:create
- Create the Entities => php bin/console make:entity 
- Create the CRUD files => php bin/console make:crud
- Make migrations files => php bin/console make:migration
- Run the Migrations => php bin/console doctrine:migrations:migrate
- Run build properties:
```sh
npm install
npm run dev
```
## Project By - yasankarj@gmail.com

