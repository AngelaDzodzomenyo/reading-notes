# **Article**

> Charts are a better way for displaying data visually than tables

> They're easier to look at and convcey data quickly

## **CHART.JS**

> JavaScript plug-in that uses HTML5's canvas element to draw the graph onto the page

### **Some Steps**
  1. need to download the plug-in
  2. draw a line chart
  3. draw a pie chart
  4. draw a bar chart

## **Basic Usage of Canvas**

### **`<canvas>` element**
  > ex: `<canvas id="tutortial" width="150" height="150"></canvas>`

  * the `<canvas>` element has only two attributes: **width** and **height**

  * its default pixels are 300 wide x 150 high

**Note: If your renderings seem distorted, try specifying your width and height attributes explicitly in the `<canvas>` attributes, and not using CSS.**

### **Rendering context**
  * canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. 
  * `<canvas>` element has a method called ***getContext()***
    * this is used to obtain the rendering context and its drawing function 

 ### **Drawing Shapes With Canvas**

 1. Coordingate space - canvas grid