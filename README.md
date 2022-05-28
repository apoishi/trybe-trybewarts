## About the Project

This repository contains the Trybewarst project developed while studying at Trybe.
In this project, I developed a Trybewarts School of Magic form page, where students can submit their feedback about the school. The theme of this project is based on J.K. Rowling's 'Harry Potter', as coding is the closest we can get to something **truly magical**!

## Skills

* Create HTML forms;
* Use CSS Flexbox to create flexible layouts;
* Create specific CSS rules to be applied to mobile devices;
* Build pages that change their layout according to screen orientation;

## Preview



## Mandatory requirements

### 1. Create a green bar at the top of the page

#### Technical Notes:

* This slash must have the `header` class
* The `header` class must determine that the element is a **flex container**
* The `header` class must have the `background-color: rgb(50, 167, 145)` property

#### What will be checked:

* There is an element with the `header` class
* Element has `display: flex` CSS property
* Element has `background-color: rgb(50, 167, 145)` CSS property

### 2. Add the Trybewarts logo with the `trybewarts-header-logo` class in the top bar

#### Technical Notes:

* There must be an img element with the `trybewarts-header-logo` class
* The `src` attribute of the logo must point to `images/trybewarts-header-logo.svg`

#### What will be checked:

* There is an `img` element with the `trybewarts-header-logo` class
* Element has `src` attribute pointing to `images/trybewarts-header-logo.svg`

### 3. Add a login form in the right corner of the top bar containing your email, password and login button

#### Technical Notes:

* The form must have the `trybewarts-login` class
* The **email** input must have the `name` attribute equal to **email** and the `placeholder` equal to **Email**
* The **password** input must have the `name` attribute equal to **password** and the `placeholder` equal to **Password**
* The button should have the text **"Enter"**
* The form must be a **flex container**
* The form must be to the right of the logo
  * **Tip:** add the flex property that makes the elements have the maximum spacing **between them** in the **header**
* By filling out the form and clicking on the button, it will be validated that:
  * If the email is **"tryber@teste.com"** and the password is **"123456"**, an alert will be issued containing the text **"Hello, Tryber!"**
  * In all other cases, an alert must be issued containing the text **"Invalid email or password."**

#### What will be checked:

* There is a `form` element with the `trybewarts-login` class
* There is an input with the `name` attribute equal to **email** and the `placeholder` equal to **Email**
* There is an input with the `name` attribute equal to **password** and the `placeholder` equal to **Password**
* There is a button with the text **"Enter"**
* The form has the `display: flex` CSS property
* The `form` element is to the right of the logo
* Clicking on the login button triggers an alert with the text **"Invalid email or password"**, in case of data filling error
* Clicking on the login button triggers an alert with the text **"Hello, Tryber!"**, if the data is correctly filled.

### 4. Create a title with the text `Trybewarts` centered inside the `Header`

#### Technical Notes:

* There must be an element `<h1>` with the **id** `trybewarts-header-title` and the text **"Trybewarts"**
* The title must be centered in the green bar
  * The header must have exactly three child elements
  * The middle child must be the title

#### What will be checked:

* There is an `h1` element with the id `trybewarts-header-title` and the text `Trybewarts`
* Element with class `header` must have exact `3` child elements
* The middle child of the element with the `header` class must be the title h1 `Trybewarts`

### 5. Add a form to the body of the page

#### Technical Notes:

* There must be a form with the id `evaluation-form`
* The form must be enclosed in a `main` tag
* Both form and `main` must be flex containers
* The form must have a width of 675px

#### What will be checked:

* There is a `form` element with the id `evaluation-form`
* The `form` element is inside the `main` tag
* The `main` element and the `form` have the `display: flex` CSS property
* The `form` element has the `width: 675px` CSS property

### 6. Make the form's main axis vertical

#### Technical Notes:

* Change main axis of form with id `evaluation-form` to vertical

#### What will be checked:

* The `evaluation-form` element has the `flex-direction: column` CSS property

### 7. Add the Trybewarts logo on the right side of the page

#### Technical Notes:

* Create an `img` element with the id `trybewarts-forms-logo`
* The `src` attribute must point to `images/trybewarts-colored.svg`
* Image must have `500px` `height` css style

#### What will be checked:

* There is an `img` element with the id `trybewarts-forms-logo`
* Element has `src` attribute pointing to `images/trybewarts-colored.svg`
* Image has css style `height` equal to `500px`

### 8. Add to the form with id `evaluation-form` the inputs of `first name, last name and email`

#### Technical Notes:

* There should be an input with the id **input-name** and placeholder **Name**
* There should be an input with the id **input-lastname** and placeholder **Lastname**
* There must be an input with the id **input-email** and placeholder **Email**

#### What will be checked:

* There is an input with the id **input-name** and placeholder **Name**
* There is an input with the id **input-lastname** and placeholder **Surname**
* There is an input with the id **input-email** and placeholder **Email**

### 9. Add to the form a select with the id `house` containing the options `Gitnória`, `Reactpuff`, `Corvinode` and `Pytherina`

#### Technical Notes:

* Must contain the option with `text` and `value` equal to `Gitnória` and with `id` equal to `gitnoria-house`
* Must contain the option with `text` and `value` equal to `Reactpuff` and with `id` equal to `reactpuff-house`
* Must contain the option with `text` and `value` equal to `Corvinode` and with `id` equal to `corvinode-house`
* Must contain the option with `text` and `value` equal to `Pytherina` and with `id` equal to `pytherina-house`

#### What will be checked:

* There is a `select` element with the id `house`
* There is an `option` element with `text` and `value` equal to `Gitnoria` and with `id` equal to `gitnoria-house`
* There is an `option` element with `text` and `value` equal to `Reactpuff` and with `id` equal to `reactpuff-house`
* There is an `option` element with `text` and `value` equal to `Corvinode` and with `id` equal to `corvinode-house`
* There is an `option` element with `text` and `value` equal to `Pytherina` and with `id` equal to `pytherina-house`

### 10. Position the `First Name` and `Last Name` fields so they are in line

#### Technical Notes:

* The `First Name` and `Last Name` fields must be side by side

#### What will be checked:

* The `Last Name` field is to the right of the `First Name` field

### 11. Position the `Email` and `Home` fields so they are in line

#### Technical Notes:

* The `Email` and `Home` fields must be side by side

#### What will be checked:

* The `Home` field is to the right of the `Email` field

### 12. Add an input field to the form to which family the student identifies

#### Technical Notes:

* Create an element with the id `label-family` and the text **"What's your family?"** should be created
* Create an `input` of type `radio` with attribute `name` equal to **family** and `value` equal to **Frontend**
* Create an `input` of type `radio` with attribute `name` equal to **family** and `value` equal to **Backend**
* Create an `input` of type `radio` with attribute `name` equal to **family** and `value` equal to **FullStack**
* Position the radio buttons to be below each other, in the sequence **Frontend**, **Backend** and **Fullstack**
* Position the radio buttons below the label

#### What will be checked:

* There is a `label` element with the `id` **label-family** that has the text content `What is your family?`
* There is an `input` of type `radio` with attribute `name` equal to **family** and `value` equal to **Frontend**
* There is an `input` of type `radio` with attribute `name` equal to **family** and `value` equal to **Backend**
* There is an `input` of type `radio` with attribute `name` equal to **family** and `value` equal to **FullStack**
* Inputs of type `radio` are one below the other in the sequence **Frontend**, **Backend** and **Fullstack**
* Inputs of type `radio` are below the label text

### 13. Create `checkbox` input fields containing six options

#### Technical Notes:

* Create an element with the `id` **label-content** and the text **"What content are you most excited to learn?"**
* Create an input of type `checkbox` with value equal to **HoFs**
* Create an input of type `checkbox` with value equal to **Jest**
* Create a `checkbox` input with value equal to **Promises**
* Create an input of type `checkbox` with value equal to **React**
* Create an input of type `checkbox` with value equal to **SQL**
* Create an input of type `checkbox` with value equal to **Python**
* Place the checkboxes below the label

#### What will be checked:

* There is a `label` element with the `id` **label-content** that has a text content `What content are you most excited to learn about?`
* There is an `input` of type `checkbox` with value attribute equal to **HoFs**
* There is an `input` of type `checkbox` with value attribute equal to **Jest**
* There is an `input` of type `checkbox` with value attribute equal to **Promises**
* There is an `input` of type `checkbox` with value attribute equal to **React**
* There is an `input` of type `checkbox` with value attribute equal to **SQL**
* There is an `input` of type `checkbox` with value attribute equal to **Python**
* The `checkbox` elements then positioned below the label

### 14. Create an input field to rate from 1 to 10 the level of satisfaction with Trybewarts

#### Technical Notes:

* An element with the `id` **label-rate** and the text **"How do you rate Trybewarts?"** should be created
* The field must be formed by ten radio buttons, containing options from 1 to 10
* Radio buttons must have the `value` attribute with the value of their options from 1 to 10.
* Radio buttons must have the `name` attribute with the value **"rate"**
* Position the radio buttons to be side by side

#### What will be checked:

* There is a `label` element with the `id` **label-rate** that has a text content `How do you rate Trybewarts?`
* There are 10 `radio-buttons` with the `name="rate"` attribute
* There are 10 `radio-buttons` containing the `value` attribute from 1 to 10

### 15. Create a textarea with the id `textarea` and a label with the class `textarea` containing the maximum number of characters equal to 500

#### Technical Notes:

* A label with the `textarea` class and the text **"Leave your comment:"** should be created
* The `textarea` field must be a maximum of 500 characters

#### What will be checked:

* There is a `label` with the `textarea` class and the text `Leave your comment:`
* The `textarea` element has a 500 character limit

### 16. Create an input field of type `checkbox` with the id `agreement` to validate the information

#### Technical Notes:

* A label with the id `label-infos` and the text **"Do you agree with the use of the information above?"** must be created
* The field must be formed by a checkbox
* The 'checkbox' field must have the `agreement` ID
* Place the checkbox next to the label

#### What will be checked:

* There is a label with the id `label-infos` that has the text `Do you agree with the use of the information above?`
* There is an input of type `checkbox` with the id `agreement`

### 17. Create a Submit button to submit the form

#### Technical Notes:

* A `submit` button must be created
* The button must have the ID `submit-btn`
* Must contain the text **"Send"**

#### What will be checked:

* There is a `submit` button with the id `submit-btn` and the text `Submit`

### 18. Make the `Submit` button enabled only after the checkbox of requirement 16 is selected

#### Technical Notes:

* The button must be disabled if the checkbox is not selected
* The button must be enabled if the checkbox is selected

#### What will be checked:

* The button is initially disabled
* The button becomes enabled, by marking the field with id `agreement`

### 19. Create a footer at the bottom of the page

#### Technical Notes:

* The footer must contain the text **"Rights reserved to Trybewarts©"**

#### What will be checked:

* There is a `footer` element must have the text `Rights reserved to Trybewarts©`

## Bonus requirements

### 20. Create a counter with the ID `counter` containing the number of characters available in the textarea, ranging from 500 to 0, which should be updated as something is typed in the textarea

#### Technical Notes:

* The counter must have the ID `counter`
* The counter must initially have the value `500`
* The counter should decrement as something is written in the `textarea` field
* The counter should increment as something is deleted in the `textarea` field
* The `textarea` element must have `id="textarea"`

#### What will be checked:

* There is an element with the id `counter`
* There is an element with the id `textarea`
* Filling in the `textarea` field changes the number displayed in the `#counter` element

### 21. Make that, when clicking on the `Send` button, the content inside the `<form>` tag is replaced by the information filled in by the user

#### Technical Notes:

* All form fields must be replaced by the user's information.
* There must be a field with the format "Name: Someone Here"
* There must be a field with the format "Email: email@mail.com"
* There must be a field with the format "House: Chosen House"
* There must be a field with the format "Family: Chosen Family"
* There must be a field with the format "Subjects: Stories, Marked, Here"
* There must be a field with the format "Assessment: NotaAqui"
* There must be a field with the format "Remarks: Remarks here"

#### What will be checked:

* The `<form>` tag with the id `evaluation-form` should be displayed on the screen
* The `checkbox` type `inputs` referring to the content list have `class="subject"`
* When clicking on the submit button, there is a text in the format `First Name: -First Name- -Last Name-`
* When clicking the send button, there is a text in the format `Email: -Email-`
* When clicking the send button, there is a text in the format `Casa: -Casa-`
* When clicking the send button, there is a text in the format `Family: -Family-`
* When clicking on the submit button, there is a text in the format `Subjects: -Selected Stories-`
* When clicking the submit button, there is a text in the format `Assessment: -Assessment-`
* When clicking the send button, there is a text in the format `Remarks: -Remarks-`
