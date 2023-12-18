Function in Javascript
Assignment Questions
Assignment Questions
Q1. Create an arrow function called square that takes a number as an argument and returns its square. Use the arrow
function to calculate the square of a given number and display the result.
Ans let square = (x) => x*x;
console.log(square(2));
OUTPUT |- 4
Q2. Create a JavaScript function called generateGreeting that takes a name as an argument and returns a personalized
greeting message. Use this function to greet three different people.
Ans function generategreeeting(name){
console.log(`namaste ${name} bhai`)
}
generategreeeting("ram")
Q3. Create an IIFE (Immediately Invoked Function Expression) that calculates the square of a number and immediately
displays the result.
Ans (function suare(x){
console.log(x*x);
})(2);
Q4. Write a JavaScript function called calculateTax that takes an income as an argument and returns the amount of tax to
be paid. Use a closure to handle different tax rates based on income ranges. Test the function with various incomes.
Ans function calculatetax(x){
if(x>800000){
let tax = (x*20)/100;
console.log(`you have to pay ${tax} as income tax`)
}
else{
let tax = (x*10)/100;
console.log(`you have to pay ${tax} as income tax`)
}
}
console.log(calculatetax(12000))
Q5. Write a JavaScript function called factorial that calculates the factorial of a non-negative integer using recursion. Test
the function with different inputs.
Ans function factorial(x){
if(x==0){
return 1
}
else{
return x*factorial(x-1)
}
}
console.log(factorial(7))
OUTPUT |- 5040
Q6. Write a JavaScript function called curry that takes a function as an argument and returns a curried version of that
function. The curried function should accept arguments one at a time and return a new function until all arguments are
provided. Then, it should execute the original function with all arguments. Test the curry function with a function that adds
two numbers.
Full Stack Web Development
