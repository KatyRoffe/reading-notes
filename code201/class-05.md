# HTML Reading

## Chapter 5 :: Images
* Images can help set the tone of a site
* `<img>` element. it is an empty element (does not require a closing tag)
  * needs a `src` attribute to link to the image and an `alt` attribute to provide a text description of the image if it can't be seen
* a `title` attribute can be included to provide additional information that will display when the user hovers over the image
* images take longer to load than the rest of the HTML, so specifying the *height* and *width* dimensions will help load the rest of the page accurately if the image is slow
* Where an image is placed will impact how the surrounding content displays on the page.
* Remember to
    1. Save images in the right format
    2. Save images at the right size
    3. Measure images in pixels
* The `<figure>` element creates an area for an image to contain a related `<figcaption>`

---

## Chapter 11 :: Color
* *RGB* values express the amount of red, green, and blue used to make a color
    * CSS3 adds RGBA which can control the opacity of an element
* *HEX Codes* are six-digit codes, preceded by a pound symbol (#), and represent the amount of red, green, and blue within the color. 
* There are 147 set *color names* that browsers can recognize
* *Hue* - how much color is in a color?
* *Saturation* - how much gray is in a color
* *Brightness* - how much black is in a color
    * CSS3 adds HSL & HSLA to help choose colors.
      * Hue is expressed as an angle between 0 and 360 degrees
      * Saturation is expressed as a percentage
      * Lightness is expressed as a percentage
        * 0% - white
        * 50% - normal
        * 100% - dark
      * Alpha property is used to define transparency and is expressed as a value between 0 and 1

<br>~ ~ ~ <br>

* Separate background colors can be set for each individual html box on a webpage
* Watch the contrast between background and foreground to make sure text is easy to read


## Chapter 12 :: Text
* Text properties can be split into two groups:
    - Those directly affecting the font and its appearance (typeface, size, emphatic markups)
    - Those that have the same effect on text no matter the font style (colors and spacing)
* Browsers will only display a typeface that is currently installed on a user's computer
* Designers recommend using no more than three different typefaces on a page
* `@font-face` allows for the use of fonts not installed on a user's computer provided the license of the typeface allows for this type of distribution
* because different browsers support different formants for fonts, to reach all types of browsers, the font variations will need to be supplied

---

# Additional Reading

[JPEG vs PNG vs GIF](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d)

* Lossless compression - no information lost during compression, images are able to be reconstructed
*Lossy compression - data loss is irreversible
* Compression artefact is the reduction in quality (distortion) of an image)

### JPEG
* Use for natural images where color and intensity variation is smooth.
* Sharp contrasts in adjacent pixels do not fare well upon compression.
* Lossy image type. 
* Don't support transparency.
* Colors: supports approx 16 million


### PNG 
* Use for any image needing transparency, such as images with text overlays.
* Lossless image type. 
* Retains higher quality than JPEG upon compression, but occupies more space on the computer.
* Supports transparency by
  * inserting an alpha channel OR
  * declaring a single color as transparent
* Partial transparency helps makes the edges smooth.
* Colors: PNG8 supports 256, PNG24 supports up to 16 million.

### GIF
* Use for animated images.
* Lossless image type.
* Supports transparency by declaring a single color as transparent.
* Does not support partial transparency, so edges that are too-detailed look begin to look jagged.
    *Dithering can help with this.
* Colors: supports 256.
