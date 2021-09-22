# Shoe-Box

My CCAPDEV Machine Project

## Description

Shoe-Box is a shoe store webapp with a login system.

## Getting Started

### Dependencies

* Windows 10
* Any code editor
* MongoDB installed

### Installing

* Download the zip file
* Run npm install
```
npm install
```

### Executing program

* (Optional) Initialize your Database by uncommenting the following code in server.js
 ```
/*
const fs = require('fs');
const shoe = require('./model/user');
let adidasData = fs.readFileSync('./model/json files/users.json');  
let adidasShoes = JSON.parse(adidasData);  
shoe.insertMany(adidasShoes);  
console.log(adidasShoes); */

/*const fs = require('fs');
const lshoe = require('./model/shoe');
let ladidasData = fs.readFileSync('./model/json files/shoebox-adidas.json');  
let ladidasShoes = JSON.parse(ladidasData);  
shoe.insertMany(ladidasShoes)  
console.log(ladidasShoes);*/
```
and in /model/user.js
```
 /* module.exports=User;*/
 ```
* Run npm server.js to run the program


## Authors

Contributors names and contact info

Raphael Andrei  Santillan

Marvin Lam

