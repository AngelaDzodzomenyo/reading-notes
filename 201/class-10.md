# JS
## Chapter 10 ERROR HANDLINGS & DEBUGGING

Defintions
1. Order of Execution - The order in which statements are processed
2. Execution Contents - There is one global execution content; plus, each function creates a new new execution content. 
3. Lexicon Scope - They are linked to the object they are definied within 



 | Executed Context |       |
 ----------------------------------- | ----------------------------------- |
* **Global Context** - Code that is in the script, but not a function |  Global scope

* **Function Content** - Code that is being run within a function. Each function has its own function context. |

* **Eval Context** - Text is executed like code in an internal function called eval() |


 | Variable Scope |       |
 ----------------------------------- | ----------------------------------- |
* **Global Scope** - If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.

* **Funciton-Level Scope** - When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope. 

**REMINDER**

> each time a new item is added to the stack, it creates a new execution context.
------------
**EACH cach time a script enters a new execution content, there are two phases of activity:**

| 1:Prepare     |then | 2:Execute    |
| :---        |    :----:   |          ---: |
| The new scope is created     |       | Now it can assign values to variables  |
| Variables, functions, and arguments are created  |         | Reference Functions and run their code     |



## Understanding Errors

### There are several types of built-in error objects in JS

| **Object**                      | **Description** |
| ----------- | ----------- |
| Error     | Generic error -the other errors are all based on this error     |
| SyntaxError   | Syntax has not been followed       |
| ReferenceError   | Tried to referece a var that is not declared/within scope|
| TypeError   | An unexpected data type that cannot be coerced       |
| URIError   | encodeURI(), decodeURI(, and simiilar methods used incorrectly      |
| EvalError   | eval () function used incorrectly        |

------------

## How to deal with errors

1. Debug the script to fix errors
2. Handle errors gracefully

### DEBUGGING WORKFLOW
> try to narrow down where the problem might be, then look for clues

Ask yourself:

1. Where is the problem?
2. What exactly is the problem?

### HANDLING EXCEPTIONS
> if you know where your code might fail, use try, catch, and finally. Each one is given its own code block.

1. Try

2. Catch

3. Finally