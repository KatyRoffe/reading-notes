# [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)
- Writing code is like putting together a puzzle
    - building components taking out of a bigger picture
- Problem domains are like putting together a puzzle with either a blurry reference picture, or no picture to go off of whatsoever
- Programmers are often not given complete information
- Problem domains can be made easier by cutting out cases and narrowing focus to a part of the problem (looking at a tree instead of a forest)
    - take a part of the problem, fully understand it, then move on to the next one (like a game tutorial level)
- Learn to understand the problem domain better by not disregarding the people bringing you the project

# Chapter 3: “Object Literals” (pp.100-105)

- **Objects:** a set of variables and functions grouped together to form a model
    - Variables become known as **properties**
      - the value can be a string, number, Boolean, array, or another object
    - Functions become known as methods
    - Names are values are referred to as **keys**
      - An object cannot have two keys with the same name
    - Literals are notations with fixed values using `{}` [found on stackoverlow](https://stackoverflow.com/questions/20998159/what-is-the-meaning-of-literal-in-the-phrase-object-literal-notation)
      - as opposed to non-literal `()`
    - Object Literals are useful for creating templates for similar items (like hotels or restaurants run by the same company) while only the *properties* would need to be changed in order to show accurate data for all such objects on a page

# Chapter 5: “Document Object Model” (pp.183-242)

- Browsers create models of webpages as they load. 
  - These are called DOM trees
  - They have 4 types of nodes
    - Document
    - Element
    - Attribute
    - Text
  - Working with a DOM tree requires two steps
    1. Accessing the element (aka element node)
    2. Use the text content, child elements, & attributes
  - Methods that find a DOM in a tree are called **DOM queries**
    - use variables to store the result of this query if you need to work with an element multiple times
    - If a query can return more than one element, the results are known as a **NodeList**
    - Creating the fastest way to an element will make a webpage load faster
  
  Methods to Return a Single Element | Methods to Return Multiple Elements
  --- | ---
  getElementById() | getElementsByClassName()
  querySelector() | getelementsByTagName()
  x | querySelectorAll()

### NodeLists
- NodeLists are a collection of element nodes
- Each node is iven an idext number, beginning with zero (0)
- The order they are stored in the same order that they appeared in an HTML page
- NodeLists are a type of object
  - so they have properties (length) and methods (item)
- When a script updates the page in a **live NodeList**, the NodeList is updated at the same time
- **Static NodeLists do no update to reflect chanes made by scripts
- elements can be selected from a NodeList usin either 
  - an array syntax (this returns results faster)
  - the item() method
- Looping through a NodeList can be used to apply the same code to numerous elements

### Get/Update Elements
- Ways to Access & Update 
  - Text Node using `nodeValue`
  - Text with `textContent` or `innerText`
  - Text & Markup with `innerHTML`
- Adding Elements
  -`createElement()`
  -`createTextNode()`
  -`appendChild()`
-Removing Elements
  - store the element to be removed as a variable
  - store the parent of that element as a variable
  - remove element from containing element

