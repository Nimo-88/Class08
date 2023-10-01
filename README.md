# Class08

## Operators and Loops
 ### Note
 
#### The do while statement repeats until a specified condition evaluates to false.
> let i = 0;
do {
  i += 1;
  console.log(i);
} while (i < 5);

#### The while statement creates a loop that executes a specified statement as long as the test condition evaluates to true. 

> let n = 0;

> while (n < 3) {
  n++;
}
> console.log(n);
// Expected output: 3


### What is an expression in JavaScript?
> In JavaScript, an expression is a combination of values, variables, operators, and function calls that produces a single result.
> ***There are two types of expressions:***
> those that have side effects (such as assigning values) and those that purely evaluate.
> The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.
> 
### Why would we use a loop in our code?
> Loops offer a quick and easy way to do something repeatedly.
> they are many kinds of loops, they all essentially do the same thing: they repeat an action some number of times. 

### When does a for loop stop executing?

> loop stops executing when the specified condition in the loop header evaluates to false.

### How many times will a while loop execute?

>It will keep executing until the condition evaluates to false. If the condition never becomes false, the loop will run indefinitely, which is known as an infinite loop.
> > it will continues repeatedly as long as a certain condition is true.
