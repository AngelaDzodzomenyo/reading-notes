# HTML Forms and JS Events

## Chapter 7

### **Several Types of Form Controls**

1. Adding Text :

  > Text input, 

  > Password input,

  > Text Area,

2. Making Choices

  > Radio Buttons,

  > Checkboxes ,

  > Drop-downboxes,

3. Submitting Forms

  > Submit Buttons,

  > Image Buttons,

  > File Upload,

### KEY FACTS

  1. To differentiate between various pieces of inputted data, information is sent from the browser to the name server using name/value pairs

## FORM STRUCTURE

`<form>` element - should always carry the action attribute and will ususally have a method and id attribute too
  
     1. actions- every <form> requires an action attribute. This is the value URL for the page 

     2. method - 
          * get: idael short froms, retriveing data from the web server

          * post: allows users to upload a file, is very long, contains sensitive data(passwords), adds info to, or deletes info from a database

    3. id - used to identify the form distinctly from other elements

----------    

## Chapter 14 Lists, Tables and Forms

Web Developer Toobar

    > Provides tools to show you the CSS styles that apply to an element when you hover over it, along with the structure of the HTML


1. Outlines - red outline shows you how much space the element takes up

2. Structure - when hovering over an element, the structure will be shows at the top of the window

3. CSS Styles - when hovering over an element, you are shown the rules that apply to that element 
------------

# JS
## Chapter 6 Events

1. Interactions Create Events
2. Events Trigger Code
3. Code Responds to Users

### **DIFFERENT EVENT TYPES**

1. UI EVENTS
2. KEYBOARD EVENTW
3. MOUSE EVENTS

### **TERMINOLOGY**

1. **FIRED** : when an events has occured, it is described as having ***fired*** or been ***raised***
      > ex. if the useris tappin gon a link, a click event would fire in the browser.

2. **TRIGGER** : events are said to ***trigger*** a function or script
      > ex. when the click event fires on an element that could trigger a script that enlarges a selected form.


### HOW EVENTS TRIGGER IS JS CODE
***Event Handling***
   > When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JS code.

   ## Steps

    1. Select the element node(s) you want the script to respond to

    2. indicate which event on the selected node(s) nwill trigger the response

    3. State the code you want to run when the event occurs