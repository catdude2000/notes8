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


A function definition (also called a function declaration, or function statement) 
consists of the function keyword, followed by:
The name of the function.
A list of parameters to the function, enclosed in parentheses and separated by commas.

The JavaScript statements that define the function, enclosed in curly brackets, {...}.
A function can refer to and call itself. There are three ways for a function to 
refer to itself:
The function's name
arguments.callee
An in-scope variable that refers to the function


Control Flow
control flow is order in which computer executes statements in a script
  A typical script in JavaScript or PHP (and the like) includes many control structures, 
including conditionals, loops and functions.
  Control flow means that when you read a script, you must not only read from
start to finish but also look at program structure and how it affects order 
of execution.


The () Operator Invokes the Function
  Using the example above, toCelsius refers to the function object, and 
toCelsius() refers to the function result.

Local Variables
Variables declared within a JavaScript function, become LOCAL to the function.
Variables with same name can be used in different functions
They're created when function starts and deleted once func has completed


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
  