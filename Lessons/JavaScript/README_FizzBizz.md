    for (let i = 1; i <= answer; i++) {
      console.log(i);
    }
    We declare a variable i and assign it 1: the initial value of the variable i in our loop. The second clause, i <= answer is our condition. We want to loop until i is greater than answer. The third clause, i++, tells our loop to increment i by 1 every iteration. As a result, if the user inputs 10, this loop would print numbers 1 - 10 to the console.


    if (i % 3 === 0) {
        console.log("Fizz");
      } else {
        console.log(i);
      }
    If the current number is divisible by 3, then print Fizz.

    if (i % 5 === 0) {
        console.log("Bizz");
      } else {
        console.log(i);
      }
     If the current number is divisible by 5, then print Bizz. 

    if (i % 3 === 0 && i % 5 === 0) {
    console.log("FizzBuzz"); }
    If the current number is divisible by 3 and 5 then print FizzBuzz.