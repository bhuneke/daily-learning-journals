#LJ Code201 - Day 4

- I liked learning more about CSS today. I'm looking forward to exploring it more.

- Function example:

'use strict';
//writing (declaring) a function doesn't do anything with the value, you are just storing the information for later use
//need to call the function for something to happen

//declare a function with the function keyword followed by the name of the
//function. After the name a set of parentheses and a block which contains
//the code that you want to run when you call it.
function myFirstFunction() { //function nameOfFunction(parameters) {
  console.log('FUNCTIONS'); //Action performed by function
  //If declare variable inside function, variable only available in that function (local scope)
}

myFirstFunction(); //Call the function (include new parameters to be calculated in need be)

var someAnimalVariable = 'hyrax';

function animalFunction() {
  var someAnimalVariable = 'loris'; //if declare variable in function, only applies within the function (local)
  someAnimalVariable = 'gnarwall'; //if reassign value of variable in function, it is universally applied (global)
  console.log('In the function scope, someAnimalVariable has the value of: ' + someAnimalVariable);
}

console.log('In the global scope, someAnimalVariable has the value of: ' + someAnimalVariable);

animalFunction();
animalFunction();

- Fork details:
  - prior to starting work, you need to make sure work is merging with the master
  - pull & update local
  - driver pulls up navigator's repo
  - click "fork" button (this creates copy of repo on the driver's profile)
  - once you have the fork, clone it (make sure to clone the fork not the original repo)
  - make a new directory in the terminal and git clone into it
  - create a new branch
  - add commit push
  - push origin branch
  - once clone, make pull request back to original navigator
