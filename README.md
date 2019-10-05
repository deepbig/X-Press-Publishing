# X-Press-Publishing
Simple RESTful API to CRUD artists, series, and issues without any login process.

Node.js, Express, SQLite3

## This app does not provide authentication process which means that it can be modified the data from others.
So, Add authentication process by yourself, or just use it only for your localhost to maintain minimum security of your data. 

## How to Use
1) clone this repository
2) in the directory, type, "node install"
```
node install
```
3) npm start (this command will generate "node server.js", and by defalt, the port is opened with 4000)
```
npm start
```
4) Lastly, copy the path of the index.html file into your browser to see the front-end!

** If the index.html does not show up the data, try this:
```
node migration.js
```
(this will create database using sqlite3 --installed by node install command)

## Did you lost your data? Do this command!
```
node seed.js
```
It will insert the seed data to the database.

### Codecademy Backend Project
I took codecademy Backend Project and this is the final project that I create from the course.
