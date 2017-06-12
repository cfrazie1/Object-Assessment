## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.


### Provide examples for all three, below:

#### Scope:  The accessibility of the functions and variables for a certain portion of the code written. (global and local scope)

Global scope
var pet = 'dog';

function printPet() {

  var otherPet = "cat"; 

  console.log(pet);
}

printPet();



#### Hoisting: Hoisting is JavaScript's way of pushing all functions and variables to the top of the scope. 

function foo() {
    var x;
    bar();
    x = 1;
}

#### Compartmentalization: Is a way to organize code so that you don't repeat key words in tags and classes.
