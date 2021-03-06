**Difference between let and const**

In this lesson, we will look at the differences between how to set a variable using the **let** and **const** keywords.

### Summary
##### Creating a variable using the let keyword
If a variable is created using the `let` keyword, you can **reassign its value that is assign a new value to the variable**. There is no need to use the `let` keyword when assigning a new value to a variable.

Example: 
```
let num = 5;      // value 5 is assigned to variable num
console.log(num); // console output will be 5
num = 10;         // the num variable is assigned a new value of 10, in this case the let keyword is not required
console.log(num); // console output will be 10
```
You can declare variables in a single line to shorten the code, for example:
```
let num = 5, newNum = 15, oldNum = 10; // value 5 is assigned to variable num, value 15 is assigned to variable newNum, value 10 is assigned to variable oldNum; the variables are separated by commas
console.log(num, newNum, oldNum);     // console output will be 5, 15 and 10
```
Declaring variables in a single line is not recommended, as this makes it difficult to read the code. Declare each variable on a separate line.
