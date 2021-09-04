# Chart.js & Canvas Reading

## [Animated Charts](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)
- charts are useful for conveying information in a concise and effective manner, but they're not always easy to make
- a good way to get started is with Chart.js, which is a JS plugin that uses the canvas element to draw a graph
- line charts, pie charts, and bar charts are available

###### [Chart.js Installation](https://www.chartjs.org/docs/latest/)

## [Canvas Basics](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
- `<canvas>` element looks like the `<img>` element, but only has height and width attributes
- when not specified, the dimensions wil default to 300px x 150px
- can be styled like a normal image (with borders or margins) but these rules don't affect the actual drawing on the canvas
    - no styling rules renders the canvas as transparent
- unlike an imae, fallback content can be defines in order for it to display in older browsers that might not support the feature
- **canvas requires a closing tag**
- canvas creates a fixed-size drawing suface
- it is initially blank and requires a script to access rendering context to draw on it
    - `getContext()`

## [Canvas: Drawing Shapes](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
- canvas grid is a **coordinate space**
- typically 1 unit on the grid corresponds to 1 pixel on the canvas
- origin of the grid is located in the top left corner at (0,0)
- canvas only supports two primitive shapes: rectangles and paths
    - all other shapes must be composed of these shapes
    - using a function to "move the pen" is considered part of the path, but does not draw anything on the screen

## [Canvas: Styles & Colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
- `fillstyle` and `strokestyle` affect the colors of the shapes drawn on canvas
- these properties will need to be reassigned for evey new color
- these shapes can be obaque or have varying levels of transparency using RGBA values for the colors
    - `globalAlpha` can be used to draw lots of shapes with similar transparency
- line styles can be modified as well by setting 
    - the width of the lines
    - the appearance of the ends of the lines 
    - corners where the ends of the lines meet
    - if a line appears as dashed
- using the `createPattern(image, type)` method can be used to render numerous similar shapes with similar gradients
- shadows can also be applied to generated shapes

## [Canvas: Drawing Text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)
- drawing text has two methods: `fillText` and `strokeText`
- fillText appears to be used for solid text
- strokeText apepars to be used for text outlines
- properties can be modified using similar styling to CSS
    - font : the font size, default is 10px sans-serif
    - textAlign : where the text rests on the page, default is start
    - textBaseline : baseline alignment, default is alphabetic
    - direction : directionality, defalt is inherit
- to obtain details about the text, `measureText()` acn be run to return a TextMetrics object