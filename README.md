# Authentication-Form
###### Technologies used: Javascript, HTML, CSS, NodeJS, PostgreSQL.
###### Working of the API was also tested on Burpsuite.

![Banner](https://github.com/poorvashetye/Authentication-Form/blob/main/public/img/ss.png)

## Prerequisite
lampp

## How to install
- Clone the repo (git clone https://github.com/aadix420/AuthLogin.git)
- Install NPM (sudo apt install npm)
- Install all the dependencies (npm install express path body-parser knex)
- Setup postgres
```
psql -U postgres
\c databasename
CREATE TABLE users (id serial not null primary key, name varchar(255)) not null, email varchar(255) not null, password varchar(255) not null);
```
- Start Npm from the source 
`npm start`
- Open https://localhost:3000 in any web browser.
