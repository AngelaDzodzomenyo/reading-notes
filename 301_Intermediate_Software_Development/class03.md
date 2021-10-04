# Readings: Passing Functions as Props

## Reading
-----------
### React Docs - lists and keys
1. What does .map() return?
  * calls a provided function on every element in the calling array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
  * use the curly braces.
3. Each list item needs a unique ____.
  * a key or a string.
4. What is the purpose of a key?
  * special string attribute that needs to be included when youre creating lists of elements
### The Spread Operator
1. What is the spread operator?
  * "spreads" the array into separate arguments.
2. List 4 things that the spread operator can do.
  * Copying an array
  * Concatenating or comnbining arrays
  * Using Math Functions
  * Adding to state in React
3. Give an example of using the spread operator to combine two arrays.
  [Image from Medium](/Users/akodojo/Desktop/Example01.jpg)
4. Give an example of using the spread operator to add a new item to an array.
  [Image from Medium](/Users/akodojo/Desktop/Example02.jpg)
5. Give an example of using the spread operator to combine two objects into one.
  [Image from Medium](/Users/akodojo/Desktop/Example03.jpg)

## Videos
-----------
### How to Pass Functions Between Components
1. In the video, what is the first step that the developer does to pass functions between components?

    * He creates a function at the state level so that he can update state

2. In your own words, what does the increment function do?

   * update the count based on what name is passed in.

3. How can you pass a method from a parent component into a child component?

   * You would use this.props method and that would be within the parent component. After that you would define what you would like to change.

4. How does the child component invoke a method that was passed to it from a parent component?
 
   * You would make the child component invoke the method passed to it by the parent by using a call. 

[Back](https://angeladzodzomenyo.github.io/reading-notes/)