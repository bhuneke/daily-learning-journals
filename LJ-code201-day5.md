#LJ Code201 - Day 5

Things learned:
- Functions:
  - declaring a parameter in a function is not really different from declaring a variable
  - function sayHi(name) {
      console.log('Hello ' + name);
    }
    sayHi('Dave');// Calling a function
  - order is important for parameters
  - input - takes in parameters that are basically local variables (can use global variables here)
  - output - return value, console.log is not an output
  - console.log input and output for best debugging practices (while learning)
  - wherever you call a function() you end up getting the return value of that function
  - return is what gets a value out of a function
  - need to include variable in the return in order to reassign the value and return something different

  - var nameArray = loudLastName('Brigitte', 'Huneke');
    properHello(nameArray);

    properHello(nameArray[0], nameArray[1]);
