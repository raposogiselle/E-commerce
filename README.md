# E-commerce
Back end for E-commerce site

# Description

A Node.js app that provides Models and a routing structure for an e-commerce back-end. Offering the user to perform CRUD operations. The app utlizes sequelize and MySQL Workbench to communicate with the database.

# Walkthrough Video Link
https://drive.google.com/file/d/1zJqGphBBFVvQtR1ODe9boT_hZ1SItmqf/view


# Installation 

Create a .env file in the root directory with the following variables:

```
DB_USER=[YOUR MySQL USERNAME]
DB_PW=[YOUR MySQL PASSWORD]
DB_NAME='ecommerce_db'
```

Next, open MySQL Workbench and run the commands found in ./db/schema.sql.

Once the DB is created, return to your code editor/terminal and run:

```
npm i
```

and

```
npm run seed
```
