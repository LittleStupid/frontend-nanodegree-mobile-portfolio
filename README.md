# About html profile:
  1.move 'load css' code into foot tags
  2.delete <script src="http://www.google-analytics.com/analytics.js"></script>

# How to make pizza page scroll smoothly:
  refactor functon updatePositions() in main.js, set document.body.scrollTop into a temp variable to avoid access the DOM every loop.
