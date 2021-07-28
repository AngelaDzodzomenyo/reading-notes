# What is CSS?
    * CSS (Cascading Style Sheets)
        * Use CSS to control exactly how HTML elements look in the browswer, presenting your markup using whatever design you prefer.

## What is it for?
    * Taking a document that is in a markup language like HTML, and using CSS to specify how that document is presented to users
        > think how a site is styled or its layout
    
    *Presenting* 
        - using CSS to change the color and size of the headings and links
        - can turn text into a layout 
        - animation

## CSS Syntax
    * Rules based language
    -If you want your main heading on your page to be large, red text: 
        h1  color:red;
            font-size; 5em
                         >enclose these properties and values with curly brackets
## Defintions
    1. Selector - Selects the HTML element that we are going to style
        * ex. < h1 > 
    
    2. Declarations - similar to HTML element content. This takes the form of property & value pairs

## Structure
    * Remember before the colon, we have property, after colon, the value.

## How To Add CSS

    * There are three ways of inserting a style sheet:
            > External CSS
            > Internal CSS
            > Inline CSS
    1. *EXTERNAL CSS*
        a. Are defined within the < link > element, inside the < head > section of an HTML page
            * ex. 
                < head >
                < link rel="stylesheet" href="mystyle.css">
                < head >

        b. An external style sheet can be written in any text editor, and must be saved w/ a .css extension

        c. The external .css file should not contain any HTML tags
    
    2. *INTERNAL CSS*
        a. can be used if one single HTML page has a unique style

        b. defined inside the  < style > element, inside the < head > section of a HTML page 

[<==BACK](https://angeladzodzomenyo.github.io/reading-notes/) 