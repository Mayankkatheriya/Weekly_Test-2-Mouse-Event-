# Weekly_Test-2-Mouse-Event-
### Hosted Link: [Click here](https://mayankkatheriya.github.io/Weekly_Test-2-Mouse-Event-/)
---

# Table of content
1. [UI](#UI)
2. [HTML Code Explaination](#HTML)
3. [CSS Code Explaination](#CSS)
4. [JS Code Explaination](#JS)

# UI:
![image](https://github.com/Mayankkatheriya/Weekly_Test-2-Mouse-Event-/assets/128832286/4710c4fe-f099-4ff5-96f1-c92ae7674eeb)

# HTML:
![image](https://github.com/Mayankkatheriya/Weekly_Test-2-Mouse-Event-/assets/128832286/0067f661-ceab-4032-827b-f46e4a2a6623)

## Explaination:
Certainly, here's the summary of your HTML code without the angle brackets:

This HTML code represents a simple webpage with the following elements and features:

* A basic HTML5 document structure.
* A viewport meta tag for responsive design.
* A title set to "Mouse-Event."
* An external stylesheet linked via a link tag.
* Two container div elements for layout.
* Within the containers, two div elements labeled "Mouse X Position" and "Mouse Y Position" along with their corresponding values (both initially set to "20").
JavaScript functionality is expected to be provided by an external script file named "Script.js," linked at the end of the page using a script tag. This script may handle updating the displayed mouse positions.

This code creates a webpage that visually represents the X and Y positions of the mouse cursor and likely includes interactivity through JavaScript for dynamic updates.

# CSS:
![image](https://github.com/Mayankkatheriya/Weekly_Test-2-Mouse-Event-/assets/128832286/6758ea83-3fa8-40bf-bc0b-5b0158d50707)


## Explaination:
Certainly, here's a shorter explanation of your CSS code:

This CSS code sets styles for different elements in the HTML document:

* It resets margins, padding, and makes elements use the "border-box" box model.
* It sets the default font to "Comic Sans MS" and changes the cursor to a crosshair.
* It styles a "container" div to fill the viewport, centering its content.
* It styles an "inner-container" div to center its content and allow content wrapping.
* It styles "mouse-event" divs, giving them borders, margin, and centering content.
* It styles the "h4" elements inside "mouse-event" divs with absolute positioning, making them appear above the divs and centered.
  
Overall, this CSS creates a centered layout with specific styling for various elements, particularly for displaying mouse position information.

# JS:
![image](https://github.com/Mayankkatheriya/Weekly_Test-2-Mouse-Event-/assets/128832286/de6bd5d5-1a87-4592-a591-a6c29a6ff7df)

## Explaination:

Certainly, here's a shorter explanation of your JavaScript code:

This JavaScript code does the following:

* It selects an HTML element with the class "inner-container" and assigns it to the variable positionBox.
* It adds an event listener to the window that listens for the "mousemove" event, which triggers when the mouse is moved.
* When the "mousemove" event occurs, it updates the content of the positionBox element with the current mouse position information using template literals (${}) to insert the values dynamically:
* It displays the horizontal (X) position of the mouse using event.clientX.
* It displays the vertical (Y) position of the mouse using event.clientY.
* The content is structured into two "mouse-event" divs, each containing the X and Y mouse positions along with corresponding headings.

In summary, this JavaScript code listens for mouse movement on the window and updates the content of the "inner-container" element to display the current X and Y positions of the mouse cursor as it moves.
