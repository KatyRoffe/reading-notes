# HTML Reading

## Chapter 4 :: Links
* Links are created by using the `<a>` element. 
* Add an `href` attribute to the opening tag, followed by the link
* Any text contained between the opening and closing tags will be converted to a hyperlink. 
* When linking to an external website, an href's value must be a full link (an **absolute url**)
* When linking to a separate page on your own site, use shorthand (a **relative url**) 
    * if the pages of the site are in the same folder, the href's value can simply be the name of the file.
    * a good practice for larger sites is to place related pages of the site (site sections) into a new folder. these folders are **directories.**
* To have a link open in a new window give the `<a>` a `target` attribute with a value of `blank`. 
    > `<a href="www.github.com" target="_blank">`
    * It is good form to inform a user when clicking a link will open a new page/tab
* Adding an `id` attribute to the sections of a page allows for linking directly to that portion of the page by making the `href` value the name of the `id`. 
    * This works for linking to a specific portion of a different page as well, provided the href value contains both the url and section id of the portion to be linked.

--- 

## Chapter 15 :: Layout
* CSS treats HTML elements as if they are all contained in separate boxes
* A **block-level** box starts on a new line and, though it may not visibly take up the full line, it owns all of it
* An **inline box** goes with the flow of the text and takes up only the space needed
* The width (and sometimes height) can be modified to change how much space the boxes use
* Visually separating the boxes can be done through use of styling the borders, margins, and background colors
* Block level elements can next other block level elements

<br>~~~<br>

#### Positioning Schemes
- **Normal Flow** :: all block level elelemnts appear on a new line 
- **Relative Positioning** :: moves elements away from where it would be in a normal flow but does not affect the position of surrounding elements
- **Absolute Positioning** :: positions an element in relation to the containing element and does not affect any surrounding elements
- **Fixed Positioning** :: aboluste positioning. positions the element in relation to the brower window as opposed to any other element on the screen
- **Floating Elements** :: allows for an element to be removed from normal flow completely / the element itself becomes a block element and everything else flows around it

---

# JS Reading

## Chapter 3 :: Function, Methods, & Objects (pp 86-99)

### Functions
* Functions are used to group statements together (and keep the code organized) to peform a specific task of code. 
* Because functions do not always execute when a page loads, they offer a way to *store* the steps of a task for later use.
* Asking a function to perform its taks is known as **calling** a function. 
* **Declare** a function by using the `function` keyword, then give the function a name/**identifier**. 
* The **statements** that perform the task reside in code block contained by curly brackets `{ }`
*Calling a function involves adding a portion of code where the function should be executed. 
  > `functionName();`

* **Function Declaration** - creates a function that can be called later
* **Named Functions** - functions that have been named in order to call them back later
* **Function Expression** - a function placed where an expression is expected
* **Annonymous Function** - an unnamed function

* **IIFE** - immediatey invoked function expressions 
    * these are not given names
    * they are used for code that only needs to be called once for a task
* Where variales are declared affects where it can be used. 
    * variables called within a function can only be used in that function
        > called *local* or *function-level* variables 
        > they have *local-scope* / *function-level-scope*
    * variables called outside a function can be used anywhere in the script
      > called *global* variables
    * 

---

# Additional Reading

[6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

* Pair programming typically involves two roles
    - The Driver: one programmer to type out the code
    - The Navigator: Thinks about the bigger picture, how an algorithm could convert to code, looks up solutions and documentation, scanns fo typos or bugs, *but does not write the code*
* Helps developers to develop four key skills
    1. Explain aloud what the code should do
    2. Listen to guidance
    3. Read code
    4. Write code

* Pair programming is helpful for six main reasons. 
    1. **Greater efficiency.** Two sets of eyes are better than one. 
    2. **Engaged collaboration.** More focused, harder to procrastinate or get off track. 
    3. **Learning from fellow students.** Different learning styles allow for unique approaches to specific problems. 
    4. **Social skills.** Different coding and communication styles provide new obstacles to overcome as a team. 
    5. **Job interview readiness.** Pair programming between an applicant and a current employee is a common step in the interview process. 
    6. **Work environment readiness.** Many companies utilize the process to train new employees on how they operate. 
