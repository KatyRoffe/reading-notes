# HTML Notes

## Introduction

### How People Access The Web
* Web Browsers :: Software people use to access websites. The manufacturers regularly release new versions with updates such as new features, bug fixes, or the supporting of additional languages. Many users do not update as frequenly as these features are issues, so a developer should not assume that all web usess are able to use the latest functionalities. 

* Web Servers :: Special computers, constantly connected to the internet, which are optimized to host websites and send the pages to users requesting them. Larger companies might run their own servers, but it is more common to pay a fee to a company to host a site. 

* Devices :: Not all devices are created equal. Devices vary in screen size and connection speeds, so a website optimized for one particular type of device may not work well on another. 

* Screen Readers :: Programs that read out the contents of a computer screen. There is legislation in place to require websites be accessible to users with disabilities. While screen readers are useful for those who have visual impairments, similar technologies are used for those who might want to "read" a screen while on the move (eg: while jogging)

## Chapter 1 || Structure
Structure helps readers/users understand a document/webpage better. Structure could be likened to an outline: breaking down a document/page into key elements to better define the layoutand keep all relevant material in places that make the most sense. 

HTML is comprised of various **elements** used to deisgn the basic structure of a webpage.  Pages composed only of HTML coding render as text pages. 

Elements always contain
 * Opening tag to denote where the element begins
 * Closing tag to denote where the element ends
 * Content that lies between them

The opening tag of an element might also include **attributes**. These contain the
* Name, which indicates what additional information is gong to be applied to the content
* Value, the setting/information of the attribute (these should always be placed in double quotation marks)

![imgexample](https://i.ibb.co/GVbdt4v/element-example.jpg)


## Chapter 8 || Extra Markup

* `<DOCTYPE>` :: tells browsers which version of HTML is being used
> since there have been numerous versions of HTML, identifying which type helps the browser to render the page correctly
* `<!-- comment -->` :: used to denote comments that will not appear in the webpage
> comments can be used to help explain the code or provide markers for where sections of the page begin and end
* `<div>` :: group block-level elements together for specific coding - useful for breaking up the page into sections
> block elements take up the entire line (ex. headers, paragraphs, lists)
* `<span>` :: group in-line elements together for specifc coding - useful for differentiating a section of text from the surrounding area
> in-line elements take up only the space that they need (ex. bold, italics, images, hyperlinks)

* `<iframes>` :: creates a "window" in the webpage to view other pages
> commonly used by sites creating an area to view google maps for directions
* `<meta>` :: allows the user to supply additional information about the webpage to the browser
> nestled in the `<head>` element, can provide info regarding a description, the author keywords, expiration for cache, etc.

* **"id" attribute** :: creates a unique identifier for a single element
> this allows specific CSS to be applied separately to this element
* **"class" attribute** :: creates a a uniqe identifier for a set of similar elements
> this allows specific CSS to be aplied separately to this set of elements

* **escape characters** :: these characters are reserved by HTML and will not appear properly without using the appropriate "escape code"/entity reference. 


## Chapter 17 || HTML5 Layout

Previous versions of HTML would require a developer to use multiple `<div>` elements with class or id attributes to divide the content of the page. HTML5 has taken some of those common attributes and turned them into elements of their own. 

* `<header>` :: appears at the top of the page, may contain title information
* `<footer>` :: appears at the bottom of the page, may contain copyright info or links for sharing
* `<nav>` :: contains major navigational links on the site; though commonly used in the header, it has also been used in the footer for additional navigation to pages on privacy policies or terms and conditions
* `<article>` :: to contain any section of a page that could stand on its own; articles could also include their own headers and footers
* `<aside>` :: when used in an article, should contain related but not essential info; when used outside an article, should contain info related to the entire page (site links, additional author writings, etc)
* `<section>` :: groups related content together, each section should ideally have its on heading; a page with a long article element may benefit from dividing the article into sections as well
* `<hgroup` (heading group):: used to group together a set of heading elements (`<h1>` through `<h6>`) to be treated as a single heading
> some prefer to place a subtitle with a `<p>` element rather than use a heading group 
* `<figure>` :: contains content referenced from the main article, typically some form of media (images, videos, etc.) though supporting text is also acceptable
> it should also include a `<figcaption>` element to provide a decription of the content
* `<div>` :: when there is no other suitable element, div can and should be used

## Chapter 18 || Process & Design

Good websites are like books: you create them wih a target audience in mind, not just to satisfy the whims of the creator. 

### Identify
1. Who comprises the target audience
2. The key motivations for visiting the site
3. The specific goals for visiting the site
4. What information the visitors need
5. How often you predict them visiting

Once a developer has these in mind, it will be easier to plan out a **site map.**

A site map is a general layout of all the pages a website might require to function at an optimal level.For example, a home decor shop might divide their wares by the room they're designed for. 

Web developers should also design a **wireframe** prior to beginning their code. The wireframe is a basic layout of how the information should be presented on the webpage. 

The visual design of a webpage should also be used to effectively communicate the information. Organizing and prioritizing the necessary content and making it stand out using a **visual hierarchy** can help to draw attention to the content that the developer wishes to highlight the most.

---

# JS Notes

## Introduction

## Chapter 1 || The ABC of Programming
