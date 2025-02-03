HTML FORM
---------

* An HTML form is used to collect user input. The user input is most often sent to a server for processing.

* The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

<input type="text">	    Displays a single-line text input field

<input type="radio">	Displays a radio button (for selecting one of many choices)

<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)

<input type="submit">	Displays a submit button (for submitting the form)

<input type="button">	Displays a clickable button

<input type="button" value="reset">	Reset all form fields




Some Validators in Form fields
------------------------------

<input type="text" placeholder="Enter your name">

* placeholder attribute hints user about what to give input to a field

<input type="number" min=100>

* Input number must be >= 100

<input type="password" minlength = 6>

* Password length must be >= 6

HTML Label
----------

<label for="flipkart">Flipkart Search</label>
<input id="flipkart" type="text" name="q">

The <label> tag defines a label for many form elements.

The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focuses on the input element.

The <label> element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <label> element, it toggles the radio button/checkbox.

The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.

