# you-me-svg
Repo for You, me, SVG course files from Code School

## Questions and comments

### Which type of image, when zoomed in, gets blurry and distorted? 

Raster images (.png, .jpeg, .gif)

### What if we wanted to scale our phone icon's button? Could we do this with CSS?

Nope! You cannot select inner elements of the SVG when you're including it with an <img>

### What if we wanted to change the color of our SVG's background?

```html
<svg height="110" width="80" xmlns="http..." ~~fill="color"~~>
```
Again, nope. We would need to do this through CSS because the SVG tag has no "fill" attribute.

### Groups

Groups allow manipulating elements in a bundle. It has the transform property with which you can:

traslate(x, y) = 
rotate(degree, x center, y center) = 
scale(0.6) = value 1 means no scaling (the reference is the top left of the frame, so you might need to translate it again)

SVG height and width is the viewport
