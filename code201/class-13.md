# [Local Storage](http://diveinto.html5doctor.com/storage.html)

- native client applications typically have an advantage over web applications when it comes to local storage
- web apps can use cookies for local storage of small amount of data
    - but cookies are included with https request and slow down the web browser by transmitting the same data repeatedly
    - cookies are unencrypted and not secure
    - cookies are limited to bout 4KB of data, slows down apps but not enough data to be useful
- HTML5 Storage is a way for web pages to store names key/value pairs locally (within the web browser)
    - this data would remain stored even after navaigating away from the website or closing the browser
    - this data is not transmitted to a remote server
    - it has 5 megabytes of storage for each origin
- use [Modernizr](https://modernizr.com/) to see if your browser supports it
