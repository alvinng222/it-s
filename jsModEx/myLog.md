JavaScript modules
==================
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

Basic example structure
In our first example (see basic-modules) we have a file structure as follows:

basic-modules: https://github.com/mdn/js-examples/tree/master/modules/basic-modules
``` js
index.html
main.js
modules/
    canvas.js
    square.js
```
Note: All of the examples in this guide have basically the same structure; the above should start getting pretty familiar.

The modules directory's two modules are described below:

- `canvas.js` — contains functions related to setting up the canvas:
  - `create()` — creates a canvas with a specified width and height inside a wrapper <div> with a specified ID, which is itself appended inside a specified parent element. Returns an object containing the canvas's 2D context and the wrapper's ID.
  - `createReportList()` — creates an unordered list appended inside a specified wrapper element, which can be used to output report data into. Returns the list's ID.
- square.js — contains:
  - `name`— a constant containing the string 'square'.
  - `draw()` — draws a square on a specified canvas, with a specified size, position, and color. Returns an object containing the square's size, position, and color.
  - `reportArea()` — writes a square's area to a specific report list, given its length.
  - `reportPerimeter()` — writes a square's perimeter to a specific report list, given its length.
