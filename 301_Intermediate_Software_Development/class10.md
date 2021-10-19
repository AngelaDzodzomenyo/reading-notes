# Readings: In Memory Storage

## [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)

1. What is a ‘call’?

  * function invocation 

2. How many ‘calls’ can happen at once?

  * One at a time fro mtop to bottom. 

3. What does LIFO mean?

  * (Last In First Out)

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

  * 

5. What causes a Stack Overflow?

  * Occurs when there is a recursive function without an exit point.

## [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

1. What is a ‘refrence error’?

  * When you try to use a variable that is not yet declared.
    > ex: console.log(foo) // Uncaught ReferenceError: foo is not definded
    > commin when using `cost` and `let`

2. What is a ‘syntax error’?

  * Occurs when you have something that cannot be parsed in terms of syntax.
    > ex: JSON.parse('foo': 'bar') // Uncaught SyntaxError: Unexpected token o in JSON at position 1

3. What is a ‘range error’?

  * Error shows up when you try to manipulate an object with some kind of length and give it an invalid length.

4. What is a ‘tyep error’?
 
  * Error shows up when the types(number, string, etc..) you are trying to use or access are incompatible.

5. What is a breakpoint?

  * Place where your code breaks(bug).

6. What does the word ‘debugger’ do in your code

  * Debugger statement in your code in the line you want to break. 