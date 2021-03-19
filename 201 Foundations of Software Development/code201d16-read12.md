# Chart.js

- Chart.js : is a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page.

- To create a chart:
   
    - Install and set up Chart.js.

    - Use `<canvas>` in the script .

- `<canvas>` element has two optional attributes, width and height.

- The `<canvas>` element can be styled like any normal image (margin, border, background…).However, these rules don't affect the actual drawing on the canvas.

- `<canvas>` element requires the closing tag `</canvas>`. If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

- `<canvas>` only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths.

-  Properties 'fillStyle' and 'strokeStyle' are used to apply colors to a shape. 

- The canvas rendering context provides two methods to render text:

    - `fillText(text, x, y [, maxWidth])` : Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

    - `strokeText(text, x, y [, maxWidth])` : Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

- 4 Awesome Things You Can Do With HTML Canvas:
   
     1. Transformation : Scale, Rotate and Translate. 
     2. Shadows : shadowOffsetX , shadowOffsetY, shadowBlur and shadowColor.
     3. Complex shapes
     4. Line Caps and Joins

![](https://4.bp.blogspot.com/-ftkhwUiztUc/WN7kQwwdAtI/AAAAAAAAlcg/kbB-xurJAQwO0av7EK93V1XwGODi42nkACLcB/s1600/Tudor%2BAnghelina%2B-%2BHTML%2BCanvas.png)