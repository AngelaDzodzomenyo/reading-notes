# Expressions and Operators

    ## Operators
        * Assignment
        * Comparison
        * Arithmetic
        * Bitwise
        * Logical
        * String
        * Conditional
        * Comma
        * Unary
        * Relational

        > binary and unary oprators
            * binary has two operands: before **and** after operator
            * unary has one operand: before **or** after operator

        1. Return value and chaining
            a. ex. const z = ( x = y ); // Or equivalently: const z = x = y
                > console.log(z); // Log the return value of the assignment x = y
                > console.log (x = y ); // Or log the return value directly

        2. Comparison operators
            a. Equal (==) - returns true if the oerands are equal
            b. Return true if the operands are not equal

# Functions
    - are one of the fundamental building blocks in JS. It is similar to a procedure -  set of statement that performs a task or calculates a value

    1. Function Declarations
        - this consists of the function keyword followed by:
            + the name of the function
            + a list of paramenters to the function, enclosed in parenthese and separated by commas
            + the JS statements that define the function, enclosed in curly brackers, { ... }

        - ex. function square(number){
                return number * number;
        }

    2. Calling Functions
        - **Defining a function does *not* execute it!**
        a. Functions must be **inscope** when they are called
            + ex. console.log(square(5));
                    function square(n) { return n * n }

# CONTROL FLOW
    - the order in which the computer executes statements in a script


