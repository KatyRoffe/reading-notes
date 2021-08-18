# HTML Reading 

## Ch. 15: “Layout” 
### (repeat of Class 4 reading)
* CSS treats HTML elements as if they are all contained in separate boxes
  - **block-level** :: new line
  - **inline box** :: flows with the structure of the contens

<br>~~~<br>

#### Positioning Schemes
- **Normal Flow** :: new line 
  - `position: static`
- **Relative Positioning** :: does not affect the position of surrounding elements
  - `position: relative`
- **Absolute Positioning** :: does not affect any surrounding elements
  - `position: absolute`
- **Fixed Positioning** :: absolute positioning. 
  - `position:fixed`
- **Floating Elements** :: removed from normal flow completely and becomes a block element
  -`float` (allows block elements to be placed side by side)
  -`clear` (no element within the same containing element should touch the side of the box (left, right, both, none))

- `z-index` property allows for overlapping boxes
- **box-offset** properties tell how far from the top, bottom, and sides a box should be placed

- sometimes an element containing nothing but floats gets treated as though the element is 0-pixels tall
  - fix this with an `overflow: auto` and `width-100%`

  - different screens have different sizes. page layouts should be able to work on a range of different sized screens
      - fixed width layouts
      - liquid layouts

- CSS Frameworks is designed to provide code for common tasks to make the design of layouts a little easier