# Operators and Loops

## Assignment

* Assignment Operator:

  * Shorthand: x = y

  * meaning: x = y

* Addition Assignment:

  * Shorthand: x += y

  * Meaning: x = x + y

* Subtraction Assignment

  * Shorthand: x -= y

  * Meaning: x = x - y

* Multiplication Assignment:

  * Shorthand: x *= y

  * Meaning: x = x * y

* Division Assignment

  * Shorthand: x /= y

  * Meaning: x = x / y

* Remainder Assignment
  
  * Shorthand: x % y

  * Meaning: x = x % y

* Exponentiation Assignment

  * Shorthand: x **= y

  * Meaning: x = x ** y

* Left shift assignment

  * Shorthand: x <<= y

  * Meaning: x = x << y

* Right shift assignment
  
  * Shorthand: x >>= y
  
  * Meaning: x = x >> y

* Unsigned right shift assignment
  
  * Shorthand: x >>>= y
  
  * Meaning: x = x >>> y

* Bitwise AND assignment
  
  * Shorthand: x &= y
  
  * Meaning: x = x & y

* Bitwise XOR assignment

  * Shorthand: x ^= y
  
  * Meaning: x = x ^ y

* Bitwise OR assignment

  * Shorthand: ```x |= y```
  
  * Meaning: ```x = x | y```

* Logical AND assignment

  * Shorthand: x &&= y
  
  * Meaning: x && (x = y)

* Logical OR assignment

  * Shorthand: ```x ||= y```
  
  * Meaning: ```x || (x = y)```

* Logical nullish assignment

  * Shorthand: x ??= y
  
  * Meaning: x ?? (x = y)

## Comparison

* Equal (==):True if operands are equal

* Not Equal (!=): True if operands are not equal

* Strict Equal (===): equal if of the same type and equal

* Strict not equal (!==): true if not equal but are the same type or equal but different type

* Greater Than (>): True if the left is greater than the right.

* Less Than (<): True if the right is greater than the left.

* Greater Than Equal To (>=): True if the left is greater than or equal to the right operand.

* Less Than Equal To (<=): True if the right is greater than or equal to the right operand.

## Arithmetic

* Remainder (%): Returns remainder of dividing two numbers 

* Increment (++): Adds one to the operand

* Decrement (--): Subtracts one from the operand

* Unary negation (-): Returns the opposite of its operand

* Unary plus (+): attempt to convert an operand to a number

* Exponentiation operator (**): Calculates base to exponent power

For more on Operaters, check out the article on [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators).

## Loops

* **Loops:** makes something happen repeatedly

* There are different loops, but they all repeat an action a certain number of times.

## Different Loop Statements

* ```for``` loop: repeats until the conditions specified condition evaluates ```false```

  * Syntax: ```for ([initialExpression]; [condition]; [increment]) statement```

* ```do... while``` statement: Repeats until the conditioned specified evaluates to ```false```
  
  * Syntax: ```do statement while (condition);```

* ```while``` statement: repeats statement as long as the condition specified is ```true```

  * Syntax: ```label:   statement```

* ```break``` statement: terminates a loop

  * using ```break``` without a label it ends the innermost enclosing ```while```, ```do-while```, ```for```, or ```switch```and then transfers the control to the next statement. 

  * ```break``` ends a specified label statements.

  * Syntax: ```break;``` //ends the innermost loop or switch
  ```break[label];``` //ends specified label

* ```continue``` statement: used to restart the ```while```, ```do-while```, ```for``` or ```label``` statements. 
  * Syntax: ```continue[label];```

* ```for...in``` statement: repeats a specified variabl over the enumerable properties of an object.

  * Syntax: ```for (variable in object) statement```

* ```for...of``` statement: repeats over iterable objects including ```array```, ```map```, ```set```, ```arguments```, objects etc...
  * Syntax: ```for (variable of object)  statement```

[Home](https://cquinn21.github.io/.github.io-reading-notes/index)