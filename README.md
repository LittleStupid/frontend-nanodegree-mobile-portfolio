# About html profile:
  1.move 'load css' code into foot tags.
  2.delete script of analytics.js.

# How to make pizza page scroll smoothly:
  refactor functon updatePositions() in main.js, set document.body.scrollTop into a temp variable to avoid access the DOM every loop.

# How to make resize pizza with less time:
  Do not set pizzas' style in the loop, batch them all at once.
