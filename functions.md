# Functions in JavaScript

* Functions are the building blocks in JavaScript.

* To qualify as a function it must take input and return an output.

* To use a function you must define it somewhere in the scope from where you wish to call.

## Defining Functions

**Function Definition** consists of the *function* keyword followed by:

    - The name of the function

    - a list of the parameters to the function enclosed in parentheses and separated by commas.

    - The JavaScript statements that define the function enclosed in the curly bracket ```{}```.

    **_Example:_** Defines a simple function ```square```:
    ```function square(number){
        return number * number;
    }```

    - Functions ```square``` takes the parameter *number* and has one statement that says to return the parameter of the function ```(number)``` multiplied by itself.

* Parameters are passed to function by **value**, value is passed to function.

  * if the function changed the value of the parameter, this change is not reflected globally or in the calling function.

* Defining a function does not execute it, it names the function and specifies what to do when the function is called.

* A method is a function that is a property of an object.

## Calling Functions

* **Calling** a function performs the specified actions with the indicated parameters you would call the function ```square``` as follows: ```square(5);```

* Functions must be in a scope when they are called, but function declarationcan be below the call in code. Example: ```console.log(square(5));```
```function square(n){return n * n}```
*_Note_* only works using following syntax: ```function funcName(){}```

Functions can be called 3 ways:

1. The functions name.
2. arguments ```.callee```
3. An in-scope variable that refers to the function.

## Nested Functions and Closures

* You can nest a function within a function. The inner, or nested, function is private to its outer, or containing function.

* **Closure** is an expression that can have free variables together with an environment that binds those variables or *closes* the expression.

* Nested function can inherit the arguments and variables of its containing function.

* Outer functions cannot use the arguments and variables of the inner function.

* **Arguments** are similar to arrays in that it has a numbered index and a length property, but it is not an array because it does not have all of the array manipulation methods.

## Control Flow

* The order in which the computer executes statements in script.

* Code runs from first line to the last in a file. Unless the computer runs into conditional loops or other structures that change the control flow. *Example:* script prompts user to fill in some information and depending on the input determines what code to execute next.

## Why Functions

* Functions are executed when something calls it.

* Reuse code 

* Same code can be used many times with different arguments to produce different results

* The ```()``` operator invokes the function. *Example:* ```theResult``` refers to the function object whereas ```theResult()```refers to the result of the function.

* **Local Variables** are variables that are declared within JavaScript function become LOCAL to the function. Local variables can only be accessed from within the function.

* Same name variables can be used in different functions sense the local variables are only recognized inside their functions.

* Local variables are created when functions start and are deleted once the function completes.

## Function Syntax

* defined with *function* keyword followed by the name and ```()```

* Can contain letters, numbers, underscores, and dollar signs.

* Parentheses may have parameter names separated by commas. *Example:* ```(p1, p2,...)```

* The executed code should be in curly brackets ```{}```

* **Parameters** are listed inside the parentheses ```()``` in function definitions.

* **Arguments** are the **values** that are received by the function when invoked.

* Code is executed when called from the function when:
  * an event occurs like a user clicking a button.

  * When called from JavaScript code.

  * Or self invoked

## Function Return

* When the return statement is reached the function stops executing.

* Functions compute a return value, the value is returned back to the caller.

## Predefined Functions

For a list of predefined functions, checkout [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions#predefined_functions). 

## Operators

* Operators are used to perfomr mathematical and logical computations.

* Capable of manipulating certain values and operands.

* For a list of different types of operators, go to [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators) or [W3Schools](https://www.w3schools.com/js/js_operators.asp).