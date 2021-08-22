# HTML Reading

## Chapter 16: Images
- dimensions can be specified using CSS
    - this is helpful when using the same sized images across multiple pages on the website
    - this also makes them load smoother due to code loading faster than images
- images can be aligned both horizontally and vertically
    - images are inline elements by default. to center them, their `display` property should be switched to a block level element
- images can also be used as a background image by creating an element
    - they can be repeated horizontally, vertically, or appear only once
    - they can scroll as the site scrolls or they can be in a fixed position
- **rollovers** are links/buttons that change styles when the mouse hovers over or clicks the image
    - create images rollover effects by moving the background position of an image
- image **sprites** are created to use an image over multiple parts of the site
    - the webpage only needs to request one image rather than multiple images, which in turn makes the site faster to load

## Chapter 19: Practical Information

#### Search Engine Optimization (SEO)
  - the process of trying to get your site nearer the top of search results
  - search engines don't just look at the site, they look at what other sites have linked to it
  - on page: look at keywords people are likely to enter into a search engine to find a site
  - there are seven essential places where these keywords can and should appear
      - page title
      - url/web address
      - headings
      - text
      - link text
      - image alt text
      - page descriptions
  - search engines look at the words beween the opent and closing `<a>` tags

#### Analytics
  - by signing up for Google Analytics, the service will provide a tracking code which can be put on every page of a site
  - every time someone loads a page o the site, the code sends data to the Google server, and then provides the owner of the site data to see how visitors use the site
  - the tracking code shuold appear just before the closing `</head>` tag
  - these analytics look at what visitors are looking at and where they are coming from

#### Domain Names & Hosting
  - domain name is the web address
  - usually an annual fee is required to keep the domain name
  - once a website is setup, it needs to be hosted on a web server
  - web servers are often run by web hosting companies
      - it is typically cheaper and more reliable for an individual user to pay for a web hosting service rather than tring to run their own web servers
  - not all hosting services support all technologies, so a user should make sure to choose one based on the technologies required in their software
  - File Transfer Protocol (FTP) allows a user to transfer the files for their computer to the site hosting company

## Chapter 9: pages 201-206
- Flash was a popular tool for adding animation, video, and music to websites
- it's no longer support by most browsers as of December 2020
- Flash was criticized because its conent did not always meet accessibility requirements
- in 2005-6, a set of JavaScript libraries were released that made it easier for users to create animated effects using JS


# Additional Reading
## [Video & Audio APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)
- using the `<video>` and `<audio>` HtML5 elements will embed media content into documents
- if the element is not given a `controls` attribute, the media will embed with no *native* playback controls. 
- by not specifying a `controls` attribute, this allows the developer to program their own controls
    - this is particularly useful because native controls are different in each browser
    - native controls are also not very keyboard accessible
- the `HTMLMediaElement` API provdes features to allow for programming these controls
    - it is available to both the video and audio elements
    - it allows for playing/pausing, stopping, rewinding, and fast-forwarding the media
    - the appearance of these controls can be styled using css