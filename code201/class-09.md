# HTMLReading

## Chapter 7: Forms
- Adding Text (text input, password input, text area)
- Making choices (radio buttons, checkboxes, dropdown boxes)
- submitting forms (submit buttons, image buttons, uploading files)
<br>

- make using a `<form>` element
- every form element requires an `action` attribute
- forms are sent using `method`, which can either be a *post* or a *get*
- `<input>` creates form controls such as *text*, *name*, and *maxlength*
    - using the `type=password` attribute blocks the text from view
    - `<textarea>` is used for multi-line text input
    - `type="radio"` allows the user to pick one of many options
    - `type="checkbox"` allows the user to pick many options
    - `type="file"` allows the uer to upload images
    - `type="submit"` submits the form to the server
- `select` creates a dropdown list. identify options using `<option value="">`
- `fieldset` keeps related controls together

## Chapter 14: Lists, Tables & Forms
- the appearance of list style markers can be altered using the properties
    - *list-style-type* 
    - *list-style-image* 
    - *list-style-position*
- table cells may appears to have different borders on different browsers
    - this can be changed by controling the properpties to make them more consistent
    - make tables clean by
      - giving cells padding
      - distinguished headings
      - alternating shaded rows
      - aligned numerals
- vertically aligned form controls are easier to use
- forms benefit from the use of styles to make them feel more interactive
    - style text inputs and text areas
    - style submit buttons
    - align the labels properly

---

# JS Reading

## Chapter 6: Events
 - interactions create events 
    - the browsers way of indicating when something has happened
 - events trigger code
 - code responds to users
   - make the site feel more interactive
<br>

- **event handling**
  - select the *element* node the script should respond to
  - indicate which event will trigger the reponse
  - state the code you want to run
<br> 

- *event listeners* are the most recent way of approaching handling events
  - they can handle multiple functions at a time
  - `element.addEventListener('event', 'functionName [, Capture])`
      - the "capture" is usally a *Boolean* set to *false*
      - sometimes extra parameters need to be set within the event listener
<br>

- Types of event
    - W3C DOM Events
    - HTML5 Events
        - submit
        - input
        - change
    - BOM Events
        - touchstart
        - touchened
        - touchmove
        - orientationchange
  - User Interface
  - Focus and Blur
  - Mouse Events
  - Keyboard Events
  - Form Events
  - Mutatoin events
  
