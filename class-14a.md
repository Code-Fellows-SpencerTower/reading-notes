[CSS Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms/)

- `transform` - allows you to position, adjust size of elements
- has 2D and 3D settings
- each dimension setting has its own set of properties and values
- syntax: `transform: scale(1.7);`
- use mult vendor prefixes for best cross-browser support

## 2D:

- `rotate` - allows to rotate 0-360 degrees
  - negative value = counterclockwise, positive = clockwise
- `scale` - change size eg `transform: scale(.50);`
- `translate` - shifts position
- `skew` - tilts on x or y axis `transform: skewX(10deg);`
- `transform origin` - takes two values - `transform-origin: 0 0/top right/ 50% 50%`

## 3D:
  
- transform takes `rotateX`, `rotateY`, or `rotateZ` e.g. `transform: perspective(100px rotateY(35deg);`
- scale - takes X, Y, or Z values
- `transform-style` - flat or preserve-3d
- Backface visibility - flips image backwards

[Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)

- `transition-timing-function`
- `transition-delay`
- `transition-duration`