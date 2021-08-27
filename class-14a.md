# [Google Teams & Psychological Safety](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html)

[psychological safety notes](https://katyroffe.github.io/reading-notes/class-14b)

# [CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)
- the `transform` property has two settings: 2D and 3D
  - each comes with their own individuals properties and values
- the transform property includes vendor prefixes in order to gain support across un broswers, and they are encouraged to be used
- 2D transformations work on the x and y axes (horizontal & vertical)
- 3d transformations work on the x, y, and z axes (adds depth)

Possible 2D transformations
- rotate (from 0 to 360 degrees)
- scale (changes the size)
- translate (similar to relative positioning, changes the position of an element)
- skew (distorts elements on the axis and alters their shape a little)
<br>

- transforms can be combined, but they must be listed in the same declaration without commas
- 3D transforms work by adding a `perspective` property

Possible 3D transformations
- rotate
- scale
- translate
- skew
<br>
(all these transforms are similiar to the 2D transforms but require the z-axis to show the depth of the transformtion)
<br>

- sometimes 3D transforms are applied on an element nested within a parent eleent that is also being transformed. to preserve the child element's transformation, use a `transform-style` property with a `preserve 3d` value
- sometimes transforms leave an element with the back end facing the user. to avoid seeing this, set the `backface-visibility` property to `hidden`.  this is particuarly useful for css animations.

# [CSS Transitions & Animations](http://learn.shayhowe.com/advanced-html-css/transitions-animations/)
- transitions alter the appearance or behavior of elements when a state change occurs without the need for JS (one state to another)
- animations allow the appearance and behaviors to be altered in multiple keyframes (multiple points of transition)

### Transitions
- four related properties: transition-property, transition-duration, transition-timing-function, transition-delay
- `transition-property` states which exact properties will be altered
    - not all properties may be transitioned
- `transition-duration` is used for setting general timing values
- `transition-timing-function` is used to set the speed the transition will move
- `transition-delay` sets how long a transition should be stalled before executing

### Animations
- animations pick up where transitions leave off
- `@keyframes`set multiple points at whch an element should undergo a transition
- animations can only apply a transition within a single property
- animation utilizes the duration, timing function, and delay properties as well
- `animation-iteration-count` will repeat the animation as many times as specified
    - `infinite` will repeat the animation indefinitely
- `animation direction` can be set to indicate how the animation will play out
    - animations can run forwards and backwards
- `animation-play-state` allows the animation to be paused upon a mouse click
- `animation-fill-mode` identifies how an animation should be styled over the course of the action


## Examples

#### [8 Wow-worthy transitions](http://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users)
Fade in, Change Color, Grow & Shrink, Rotate, Square --> Circle, 3D shadow, Swing, Inset border.
Like all of them. Visually simple, but will make a site interesting. Swing is my favorite. Reminds me a bit of video games where the menu has signs that shift when you hover over them. 

#### [6 Buttons animated](http://codepen.io/retyui/pen/ByoaXV)4
Floating buttons. Love it.

#### [Keyframes](http://codepen.io/akshaychauhan/pen/oAfae)
Falling ball. Interesting.

#### [404](http://codepen.io/kieranfivestars/pen/MYdQxX)
404 massive flex. HATE this. 

#### [Bounce Animation](http://codepen.io/dp_lewis/pen/gCfBv)
Ball bounce + transform to box. Really cool. Want to experiment. No idea where.