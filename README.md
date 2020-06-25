1. In app.js, make sure all the HTML has loaded before using jQuery. (hint)

2. Create an <input> with a type="submit", id="btnSubmit", and value="Submit" in the index.html. Open the index.html in a browser and verify that a button appears.

3. In app.js and use jQuery to select the <input> element you just created by the id.

4. Add a click event handler to the <input> button that will alert a message in the browser when the button is clicked. (hint)

5. In the index.html, create a <form> element with an <input type="text"> field and the <input type="submit"> you already created.

6. In app.js when the form is submitted, alert the value of the text input field. (hint) (hint)
If the user has typed in the input field then the button should be enabled, otherwise the button should be disabled. (hint)

7. Create a div element and append it to the body.

8. When the user types in the input field and clicks submit, append the text in an h2 element to the div
When the user mouses over the h2 element, assign it a new background color and border radius. (hint)

9. Great job! Now, comment out the code for creating the h2 and we are going to work on creating a list instead
Use jQuery to create an unordered list and append it to the body

10. When the user submits the form, append the text as list item to the unordered list
When the user clicks on the li element, assign it a random color.

11. When the user double clicks on the list, remove the item that was clicked on. (hint)


Hints
jQuery on method: http://api.jquery.com/on/
jQuery click method: https://api.jquery.com/click/
Math.random() can be used to generate a random number
RGB colors range from rgb(0, 0, 0) for black to rgb(255, 255, 255) for white
You will want to generate 3 random numbers between 0 and 255 and set the RGB values using jQuery
Submission
Commit your changes and push to your GitHub profile.