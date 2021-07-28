# notes8
notes from reading 8
Operators
  JS has both binary and unary operators and one special ternary operator, 
the conditional operator.
  A binary operator requires two operands, one before the operator and 
one after the operator
  A unary operator requires a single operand, either before or after the 
operator
assignment operators assign value on left by value on right  =
  The conditional operator is the only JavaScript operator that takes three
operands. 

assignments have a return value
  That means that (x = y) returns y, (x += y) returns the resulting sum x + y,
(x **= y) returns the resulting power x ** y
  In the case of logical assignments, (x &&= y), (x ||= y), and (x ??= y), the 
return value is that of the logical operation without the assignment, so 
x && y, x || y, and x ?? y, respectively.

 the destructuring assignment syntax is a JavaScript expression that makes it
possible to extract data from arrays or objects using a syntax that mirrors the 
construction of array and object literals.
  A comparison operator compares its operands and returns a logical value based on 
whether the comparison is true.
  An arithmetic operator takes numerical values (either literals or variables) as 
their operands and returns a single numerical value.
  A bitwise operator treats their operands as a set of 32 bits (zeros and ones), 
rather than as decimal, hexadecimal, or octal numbers.
  The bitwise shift operators take two operands: the first is a quantity to be 
shifted, and the second specifies the number of bit positions by which the first
operand is to be shifted.
  in modern code you can use the new Nullish coalescing operator (??) that works like ||, 
but it only returns the second expression, when the first one is "nullish", i.e. null 
or undefined
  The conditional operator is the only JavaScript operator that takes three operands. 
The operator can have one of two values based on a condition.
  The comma operator (,) evaluates both of its operands and returns the value of the last 
operand.
  When you delete an array property, the array length is not affected and other elements 
are not re-indexed.
  The typeof operator returns a string indicating the type of the unevaluated operand.
  The void operator specifies an expression to be evaluated without returning a value.
  Use instanceof when you need to confirm the type of an object at runtime. 
 
 
Expressions
An expression is any valid unit of code that resolves to a value.
  there are two types of expressions: with side effects (for example: those that assign 
value to a variable) and those that in some sense evaluate and therefore resolve to a value.
  The grouping operator ( ) controls the precedence of evaluation in expressions.
  Left values are the destination of an assignment.
  The super keyword is used to call functions on an object's parent


Loops
A for loop repeats until a specified condition evaluates to false.
  The do...while statement repeats until a specified condition evaluates 
to false.
  A while statement executes its statements as long as a specified condition 
evaluates to true
avoid infinite loops
  A label provides a statement with an identifier that lets you refer to it 
elsewhere in your program.
  Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.
When you use break without a label, it terminates the innermost enclosing while, do-while, for, or 
switch immediately and transfers control to the following statement.
When you use break with a label, it terminates the specified labeled statement.
  The continue statement can be used to restart a while, do-while, for, or label statement.
  The for...in statement iterates a specified variable over all the enumerable properties of an object. 
For each distinct property, JavaScript executes the specified statements.
  it is better to use a traditional for loop with a numeric index when iterating over arrays, because the 
for...in statement iterates over user-defined properties in addition to the array elements, if you modify 
the Array object 
  The for...of statement creates a loop Iterating over iterable objects (including Array, Map, Set, 
arguments object and so on), invoking a custom iteration hook with statements to be executed for the 
value of each distinct property
  

  [Go to TOC](https://catdude2000.github.io/reading-notes/)