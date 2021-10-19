# Readings: FUNCTIONAL PROGRAMMING

## Functional Programming Concepts

1. What is functional programming?

  * A style of building the structure and elements of computer programs 

2. What is a pure function and how do we know if something is a pure function?

  * A pure function returns the same result if given the same arguments(it is also referred to determininistic). 

  * It does not cause any observable side effects 

3. What are the benefits of a pure function?

  * The code is easier to test.

  * No need to mock anything 

4. What is immutability?

  * unchanging over time or unble to be changed. When data is immutable, its state cannot change after it's created.

5. What is Referential transparency?

  * referential transparency = pure functions + immutable data

## Node JS Tutorial for Beginners #6 - Modules and require()

1. What is a module?

  * Split code up into nodule modules. Another javascript file. Call it when needed.

2. What does the word ‘require’ do?

  * on the global object in Node.js so can use it wherever. 

3. How do we bring another module into the file the we are working in?

  * require('./');  <----creates a path 
 

4. What do we have to do to make a module available?

  * then need to explicitly say: module.exports = function;