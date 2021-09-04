# HTML Reading

## Chapter 2 :: Text
HTML elements are used to provide structure and semantics to a webpage. 

#### Structure
`<h1>` through `<h6>` :: headings

`<p>` :: paragraphs

`<b>` :: bold

`<i>` :: italics

`<sup>` :: superscript

`<sub>` :: subscript

`<br>` :: creates a line break

`<hr />` :: creates a line through the empty space between two lines


Whitespace is the area between lines of code. If there are multiple spaces, they are collapsed into one space on the rendered webpage. 

#### Semantics
These add extra information about the content without altering the structure. 

`<strong>` :: indicates strong importance of the content

`<em>` :: indicates emphasis that could change the meaning of a phrase depending on where it's placed

`<blockquote>` :: long quotes that take up full paragraphs

`<q>` :: short quotes that sit within a paragraph

`<abbr>` :: abbreviations and acronyms

`<cite>` :: citations

`<dfn>` :: definitions

`<address>` :: contains the author's contact details

`<s>` :: used to indicate something that is no longer accurate/relevant but should not be deleted

`<del>` :: used to indicate text that has been deleted from the content

`<ins>` :: used to indicate text that has been added to the content


## Chapter 10 :: Introducing CSS
CSS styles the visuals of the content. It associates rules with HTML elements and uses those rules to know how the element should be displayed on the webpage. 

CSS rules contain a **selector** (what element the rule applies to) and a **declaration** (the style of the rule). 

Declarations have a **property** (the aspect of the element that is going to be styled) and a **value** (the setting of the property)

External CSS :: a stylesheet created separately from the HTML and linked in the `<head>` element
Internal CSS :: a `<style>` element, usually contained in the `<head>` element, containing the style rules
-- good for a single page site or an individual page that differs from the remainder of the site

For two or more rules applying to the same element:
 * if the selectors are identical, the last rule will overwrite the previous rules
 or
 * if one of the selectors is more specific, it will take precedence
 or
 * `!important` can be added after a value to indicate it should take precedence

---

# JS Reading

## Chapter 2 :: Basic JS Instructions

Scripts are made from a series of steps. Every step is called a **statement.**
- Every statement should begin on a new line
- Every statement should end in a semicolon (it indicates the step is over and to move to the next one)
- JavaScript is case sensitive

Use **comments** so explain the code. They make it easier to read an understand for anyone who might view it. 
- Single line comments should be preceded by  `// `
- Multi-line comments should begin with `/*` and end with `*/`

**Variables**  store data temporarily for the script. 
- Since scripts can be run multiple times, variables are data that could be changed to create different results
- Variables must be **declared** and given a name (an *identifier*) in order to be used
- - Identifiers are typically written in *camelCase.* ex: `var typeOfCat`
- Once a variable has been created, it can be assigned a value. ex:`typeOfCat = "calico";`

Variables have three main **data types.**
* numeric (numbers)
* string (text or numbers contained within quote marks)
* boolean (true or false values)

Six rules for naming variables.
1. Must begin with a letter, a dollar sign ($) or an underscore (_)
2. Must not contain a dash (-) or a period (.)
3. Must not use **keywords** or *reserved* words
4. They are case sensitive
5. They should describe the information the variable will store
6. Use camelCase

**Arrays** stores **lists** of *related* values. 
- They are helpful when you do not know how many items a list will contain
- Items in an array are separated by commas
- They are given a name like any other variable
- Data in an **array literal** is listed in square brackets. ex: `typeOfCat = ['calico', 'tuxedo', 'ginger'];`
- Data in an **array constructor** is listed in a parentheses and each value is on a separate line
- Each item in an array is assigned an identifying number (an **index**)
- - indexing starts with zero (0) as opposed to one (1)

**Expressions** evaluate into a single value and rely on **operators** to calculate that value.  


## Chapter 4 :: Decisions & Loops (pp 145 - 162)

Scripts may need to behave differently depending on user interaction. To determine what kind of path to take when it comes to scripts, there are three basic concepts to be considered.

**Evaluations** :: Analyzing the values in the script and whether or not they match the expected results
**Decisions** :: Using the results to decide on a path
**Loops** :: Using the same set of instructions repeatedly to achieve varying results

Flowcharts can help in planning a script and determining the number of paths available to follow. 

Decisions have two components:
* An expression is evaluated and returns a value
>- The code checks the status of the scripts by comparing two values then returning either true or false (a Boolean)
* A conditional statement says what to do in a given situations
-- Based on the concepts of if/then/else

Comparison Operators
* A condition typically has one comparison operator and an operand on either side
* The operand does not need to be a single value - it can be an *expression*

Logical Operators
* Allow you to compare the results of more than one comparison operator
* Evaluated from left to right

If Statements
* When the **if** statement evaluates a condition to be *true,* additional code is executed
* When the statement evaluates a condition to be *false,* the remaining code in the code block are not run

If..Else Statements
* When the **if** statement is *true,* a specific block of code is executed
* When the statement is *false,* a different block of code is executed



---

# Additional Reading
[Effective Git Commit Notes](https://chris.beams.io/posts/git-commit/)

* Be *concise* and *consistent* to best convey the context of a change within a project. 
* It should focus more on the *"why"* than the *"what"*. 
* If more than a single line is needed, follow these seven rules

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

> From "How to Write a Git Commit Message" by Chris Beam - [seven rules](https://chris.beams.io/posts/git-commit/#seven-rules)
