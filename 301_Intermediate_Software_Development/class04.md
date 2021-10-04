# Readings: React and Forms

### React Docs - Forms
---

* What is a ‘Controlled Component’?

    *   An input from form element whose value is controlled by React 

* Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

    * It should update the state with their response as soon as they enter them. With every keystroke the handle change runs.

* How do we target what the user is entering if we have an event handler on an input field?

setState use e.target.value. 

### The Conditional (Ternary) Operator Explained
----------

* Why would we use a ternary operator?
    *  Can write and if else statement on one line

*  Rewrite the following statement using a ternary statement:  

if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

Rewrite: 

     x === y ? true : false; 
