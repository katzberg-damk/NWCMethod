# Supplier - Recipient problem with broker 

 North-West corner Method for 1st estimation and table optimization for the supplier - recipient problem with broker. 
 
 The project for logistic and optimization classes at University.

 The assignment was to make optimization algorithm with North-West corner method as a first estimation for the supplier - recipient problem with broker. 

 It could be done as CLI but GUI was additional effort rewarded with better score. I was free to choose technology for project.

## Tech:
I choose technology based on my personal interest:

### Rust - One of new(version 1.0 in 2015) low level programing language:
* no garbage collector -> ownership and lifetime approach (like smart pointers in C++)
* default const variables
* more functional aproach
* Build in Linter that ensure safety(if it runs it won't leek)
* Less OOP, only traits with structs and Enums
* And a lot more ...

Rust is used as wasm functions.
I use serde for serialization.


### Front-End - First idea is to make it in veu.js but as I m not familiar with this technology it maybe naive idea.

**Currently** i use simple html with js for prototype.

Vue - The Newest of Big Tree JS frameworks for Front-End (React, Angular, Vue):
* Fast
* Lightweight
* Renders dom diffrence (Angural) rather then whole (React)




## ToDo:

* High Priority:
    -  [ ] Fixing alfa beta algorithm
    -  [ ] Adding tests for logic of program
* Mid Priority:
    -  [ ] Finishing html
    -  [ ] Finishing js
    -  [ ] Adding some css
    -  [ ] Connecting our site with logic written in rust using webassemby
* Low Priority:
    -  [ ] Better naming as some of them are 1 to 1 translation from polish
    -  [ ] Better structutre of files



