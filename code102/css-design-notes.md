# What is CSS?
CSS stands for Cascading Style Sheets. It is used to changed how HTML elements appear. While certain HTML elements have some basic default visual coding, these can be adjusted by CSS. 

The file used for CSS is known as a style sheet. 

## Declarations

CSS declarations are made up of a "property" and a "value" pair. Each declaration should be ended with a semicolon.

If a designer wanted to change the appearance of a level one heading so that the words appear blue it would be coded as follows:

'h1 {
    color: blue;
    font-size: 10;
}`

(insert snippets of examples later so they display properly)

Part | Example | Purpose
----- | ----- | -----
Selector | h1 | this designates which part of the HTML element is going to be affected
Property | color | indicates what the intention of the code is going to be
Value | blue | indicates how the property will be changed


## Three Ways to Insert CSS

### External CSS
Utilize an external style sheet. Any HTML page using this sheet must include a `<link>` reference in the `<head>` section to the style sheet in order for the customization to appear properly. 

`<link rel="stylesheet" href="stylesheetname.css" type="text/css>`

This is the most common practice as it is easier to maintain by keeping them in separate files. 

### Internal CSS
Code can be written within the HTML file by enclosing the code in `<style>` tags within the `<head>` section. This is useful if a single HTML page has a unique stype separate from the rest of the project. 

### Inline CSS
CSS can be directly added to HTML elements by adding a `<style>` attribute in the elements opening tag. 

`<h2 style="text-align: center; color: green; font-size: 25px;">`


[Return to Home Page](https://katyroffe.github.io/reading-notes/)







