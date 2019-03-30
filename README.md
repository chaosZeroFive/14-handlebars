# Burger Application

Node based application using express and handelbars to render html content
---

## Getting Started

---

## Prerequisites

- Your favorite code editor...such as [Visual Studio Code](https://code.visualstudio.com/)
- Latest version [node.js](https://nodejs.org/en/)
- Latest version [MySQL Community Server](https://dev.mysql.com/downloads/) MySQL Workbench is also recommended, and installs from the web

---

## NODE Dependencies

[Dotenv](https://www.npmjs.com/package/dotenv) zero-dependency module that loads environment variables

[CLI Table](https://www.npmjs.com/package/cli-table) renders unicode-aided tables in the applications terminal

[Inquirer.js](https://www.npmjs.com/package/inquirer) collection of common interactive command line user interfaces

[MySQL](https://www.npmjs.com/package/mysql) node.js driver for mysql

[Express-Handlebars](https://www.npmjs.com/package/express-handlebars) express-handlebars view engine

---

## Installation

### Clone the Repository
> git clone https://this-repository

### Install dependencies
  > npm install

### Configure Environment Variables
Create a new file in the root directory named .env

Add the code below to the .env file, save, and close
```
    DB_HOST = <hostname>
    DB_PORT = 3030
    DB_USER = <your user name>
    DB_PASS = <your password>
```
Open MySQL Workbench to the local instance created during installation

Click add SQL ![alt](https://github.com/chaosZeroFive/14-handlebars/blob/master/demo/add-sql.PNG)

Copy the contents of seed.sql to the SQL editor in Workbench

Click the Execute button ![alt](https://github.com/chaosZeroFive/14-handlebars/blob/master/demo/run.PNG)

You should see a message that indicates your action was successful ![alt](https://github.com/chaosZeroFive/14-handlebars/blob/master/demo/success.PNG)

Your root directory should look like this

```
    ./14-handlebars
        ./config
            connection.js
            orm.js
        ./controllers
            burger_controller.js
        ./db
            schema.sql
            seed.sql
        ./models
            burger.js
        ./node_modules
        ./public
            ./assets
                ./css
                    style.css
                ./img
                    burger.png
                ./js
                    app.js
        ./views
            index.handlebars
            ./layouts
                main.handlebars
        .env
        .gitignore
        package-lock.json
        package.json
        server.js
```

## How to Use

Open a Terminal, navigate to the root directory, and type:
> node server

## How it Works

