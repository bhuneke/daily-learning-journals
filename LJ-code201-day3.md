#LJ Code201 - Day 3
Things learned:
  - The difference between null(not default) and undefined(default) is intention.
  - Falsey values: zero, false, undefined, null, NaN, empty string
  - Array:
    - use when need to search a list of things or when order is important
    - var myArray = []
    - first item is 0, last item is length of array (myArray.length) -1
    - myArray.push('thing') will add to end of Array
  - While loop:
    - typically used when want something to run indefinitely
    - in condition can't be evaluated to false, while loop will continuously run and therefore crash browser
    - var count = 0;
      while (count < 1) {
        console.log(count);
        count += 1;
      }
  - For loop:
    - used to iterate over arrays or to run loop a fixed number of times
    - for (var = 0; i < myArray.length; i += 1){
      
    }
  - Today I felt like the Terminal navigation and git stuff sunk in a bit more.
