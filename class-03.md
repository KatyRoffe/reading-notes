# HTML Reading

## Chapter 3 :: Lists

#### Ordered Lists
* lists where every item is numbered
* good for step-by-step instructions or rankings
* uses the `<ol>` element with nested `<li>` elements

#### Unordered lists
* lists that begin with a bullet point
* no numerical order necessary for these lists
* uses the `<ul>` element with nested `<li>` elements 

#### Definition lists
* set of terms and their definitions
* uses the `<dl>` element with the `<dt>` element used to contain the *definition term* and the `<dd>` element used to contain the defintion

#### Nested Lists
* sublists can be nested within the main list
* simply add another set of `<ul>` and `<li>` under the appropriate item (for example, in a list about types of desserts, under the list item "pie" could be another list for types of pie)

## Chapter 13 :: Boxes
CSS treats each HTML elements as though it belongs in its own box. The appearances of these boxes can be motified through use of:
* changing the dimensions
* setting padding or margins
* adding borders
* showing or hiding boxes

### Dimensions 
* boxes are. by default sized just large enough hold their content
* sizes can be specified by use of pixels, percentages, or ems
  * percentages are based on the size of the window
  * ems are based on the size of the text
  * percentages and ems are becoming more popular due to the flexibilty of appearance across device screens
* minimum and maximum width can be specified to accomodate window and screen size
> `min-width` , `max-width` 
* minimum and maximum height can be specified to accomodate the amount of content in the box
>`min-height` , `max-height`
* overflow tells the browser what to do when the content in a box is larger than the box
  * the content can be **hidden** from view OR
  * a **scroll** bar can be added to the box 

### Borders, Margins, & Padding
All boxes have borders whether visible or invisible. 
* Borders separate the edge of one box from another
* Margins sit outside of the edge of the border and create gaps between them
* Padding is the spave between the border and the contents of a box
* Margins and padding help add space between the block items on a page
* Border width, style, and color can all be modified through CSS
* The `display` element can turn an inline element into a block-level element and allow room for additional types of formatting

---

# JS Reading

## Chapter 4 :: Decisions & Loops (162-182)

### Switch Statements

* Switch statements begin with a `switch` value
* The statements are made up of **cases** that determine whether or not a certain piece of code should be run
* Every case should be followed by a `break` keyword to indicate that portion has ended
  - So, for a 3-level switch element (level one, level two, level three), if the requirements for the variable match level two, then the level two case code would run
* The full statement resides in a single code block

### Loops
 * Loops check a condition , and it it's true, a code block will run
    - Loops are like a kid asking for candy over and over again until it hears the answer it wants OR the parent puts them in time out
  * **For** loops should be used to run the loop a predetermined number of times
  * **while** loops should be used when the developer does not know how many times the loop will need to run
  * **Do..While** loops run the statements at least once even if the conditions evaluate to false
  * **Loop Counters** can be set for conditions, used to create a set amount of times for the loop to run
  * They are particularly helpful when dealing with arrays
  * If a condition never returns false, it will trigger an *infinite loop* and eventually break the script
  