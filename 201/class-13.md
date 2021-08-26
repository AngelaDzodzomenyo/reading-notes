# **A**RTICLE 
## **THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS**

*userData* allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.

## ***HTML5** Storage*
> it is a way for webpages to store named keu/value pairs locally, within the client web browser. 

> from your JS code, you'll access HTML5 Storage through the localStorage object on the global window object.   
  * always detect whether the browser supports it

  **check for HTML5 Storage**


  `function supports_html5_storage() {`

  `try {`

  `return 'localStorage' in window && window['localStorage'] !== null;`

   `} catch (e) {`

  `return false;`

  `}`

`}`

------------
**Instead of writing this function yourself, you can use Modernizr to detect support for HTML5 Storage.**

> ex:

  `if (Modernizr.localstorage) {`

  // window.localStorage is available!

`} else {`

  // no native support for HTML5 storage :(

  // maybe try dojox.storage or a third-party solution

`}`


--------------
# Key Facts 
1. HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retreive that data with the same key.
2. The named key is a string

# Tracking Changes to the HTML5 Storage Area'

> If you want to keep track programmitically of when the storage area changes, you can trao the storage event. 

## Limitations in current browsers

> “5 megabytes” is how much storage space each origin gets by default.

> “QUOTA_EXCEEDED_ERR” is the exception that will get thrown if you exceed your storage quota of 5 megabytes.

> “No” is the answer to the next obvious question, “Can I ask the user for more storage space?” 


