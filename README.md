# Calculator App Using HTML, CSS and Javascript
![result](https://github.com/antonismpats/CalculatorApp/assets/161160300/47d5df52-f582-4231-a27a-63f53bc98c93)

## Overview
The calculator provides a mechanism for users to enter numbers and perform calculations.
The input field allows users to type numbers directly or use the provided buttons for convenience.
The calculator buttons are designed to perform specific operations such as addition, subtraction, multiplication,
division, and clearing the input. Each button has a distinct visual style and performs its intended function when clicked.

## Design
The calculator has a design with a dark theme and contrasting button colors. 
The use of box shadows and rounded corners adds depth and dimension to the interface, enhancing the overall user experience.

## Functionality
The calculator app utilizes JavaScript to provide interactive functionality, such as updating the display in real-time as 
the user inputs numbers and performing calculations when the user clicks the equal button. This adds interactivity and 
enhances the usability of the application.

## About HTML

This HTML code has the following components:

-A container div with a class of "container" to hold the calculator. <br />
-A calculator div with a class of "calculator" to contain the form. <br />

### A form containing: <br />

-A display area for the calculator result, implemented using an input field with the type "text". <br />
-Calculator buttons for numbers, arithmetic operations, and clearing the display. <br />
-Each button has an onclick attribute that triggers JavaScript functions to update the display accordingly. <br />

## About CSS

This CSS file styles the calculator app created in the HTML code. Here's a summary of the styles applied: <br />

-All elements have their margin and padding set to 0, and the box-sizing property set to border-box to include <br />
padding and border in the element's total width and height calculations. <br />
-The container class styles the container div to occupy the full viewport height, with a background color of  <br />
#79d7a2 (light green). It uses flexbox to center its content both horizontally and vertically. <br />
-The calculator class styles the calculator div with a background color of #1e2c3a (dark blue), some padding <br />
and a border-radius to give it rounded corners. <br />

### The calculator form input styles the calculator buttons: <br /> 

-They have no border or outline, a circular shape with a width and height of 60px, and a border-radius of 100px <br />
to make them circular. They have a box-shadow for a 3D effect and a transparent background. <br />
-They use a white font color, have a font size of 20px, and a cursor set to pointer to indicate interactivity. <br />
-They are spaced out with a margin of 10px. <br />
-The font weight is set to 500. <br />

### The form .display styles the display area of the calculator: <br />

-It uses flexbox to align its contents horizontally. <br />
-The input field inside it is styled with a text-align of right, a flex-grow property to fill the available <br />
space, a larger font size, a forest green border, and some padding on the right. <br />
-The form input.equal styles the equal button to have a width of 145px. <br />
-The form input.operator styles the operator buttons to have a color of #34e778 (light green) and a font weight of 600.<br />

These styles combine to create a visually appealing and functional calculator app.

