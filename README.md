# Javascript-Notes
Here you will find all basics to advance notes

## Variable
1. A variable is a container for a storing value, like a number, string.. or it is simply a name of storage location.
2. There are two types of variables in JavaScript : **local variable and global variable.
3. There are some rules while declaring a JavaScript variable. Name must start with a letter **(a to z or A to Z), underscore( _ ), or dollar( $ ) sign.**
```
  var num  // declared num variable
  var abc = 4 // declared and initialize abc variable
```
### Variable types
There are three different ways to make a variable
1. var
2. let
3. const

## Data Types
1. Number
2. String
3. Boolean
4. Undefined
5. null

## Conditional Statements
1. if-else
2. switch
3. tarnary operator

### if...else statement
if statement to execute a statement if a logical condition is true. Use the optional else clause to execute a statement if the condition is false.
```
if (condition) {
  statement1;
} else {
  statement2;
}
```
compound the statements using else if to have multiple conditions tested in sequence,
```
if (condition1) {
  statement1;
} else if (condition2) {
  statement2;
} else if (conditionN) {
  statementN;
} else {
  statementLast;
}
```
### switch cases
```
let a = 2;

switch (a) {
  case 3:
    alert( 'Too small' );
    break;
  case 4:
    alert( 'Exactly!' );
    break;
  case 5:
    alert( 'Too big' );
    break;
  default:
    alert( "I don't know such values" );

```
Here the switch starts to compare a from the first case variant that is 3. The match fails.
Then 4. That’s a match, so the execution starts from case 4 until the nearest break.
**If there is no break then the execution continues with the next case without any checks.**

### ternary operator
```
condition ? exprIfTrue : exprIfFalse
```
condition = An expression whose value is used as a condition.
exprIfTrue = An expression which is executed if the condition evaluates to a truthy value (one which equals or can be converted to true).
exprIfFalse = An expression which is executed if the condition evaluates to a truthy value (one which equals or can be converted to true).

```
const age = 26;
const beverage = age >= 21 ? "Beer" : "Juice";
console.log(beverage); // 
```

## Functions
1. We can think of functions as a way to group a set of instructions together and execute them as a single unit.
                                          or
  A function is a block of code that performs a specific task. JavaScript functions are basically used to encapsulate logic, making that   code more reusable and easier to understand.

2. Function has three two parts - Function declaration and Function call 
3. Arguments and Parameter
4. Return statement

```
function square(number) {  // function declaration , number is parameter
  return number * number;
}

var res =  square(2)       // function call statement , 2 is argument
```

```
 
## Array

