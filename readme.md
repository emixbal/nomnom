# nomnom API - nodejs

## Requirements
- nodejs
- mysql

## Installation (DEV)
- create database named "nomnom" on MySQL
- cd to deserved folder
- Clone the project:
```
$ git clone TBD
```
- Change dir to cloned project:
- create (duplicate and rename .env_sample) .env file that contain your app setting. 
```
$ cd nomnom
$ npm install
```
- this app using sequelize to mysql db connecting and model. You should install sequelize cli globaly
```
$ sudo npm install -g sequelize-cli 
```
- Migrate all tables:
```
$ sequelize db:migrate
```
- Run the server:
```
$ npm start
```


Congratz!! Now check on browser http://localhost:3000, to view the API Lists doc that you can play around!
