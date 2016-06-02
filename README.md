# About html profile:
  1.move 'load css' code into foot tags
  2.delete <script src="http://www.google-analytics.com/analytics.js"></script>



# How to make pizza page scroll smoothly:
  1.refactor functon updatePositions() in main.js, set document.body.scrollTop into a temp variable to avoid access the DOM every loop.
  2.use -webkit-backface-visibility: hidden;
        backface-visibility: hidden;
    in views/css/style.css file.
  3.Change document.querySelectorAll into document.getElementsByClassName.
  4.Generates sliding pizzas dynamically.


# How to make resize pizza with less time:
  1.Do not set pizzas' style in the loop, batch them all at once.
  2.Change document.querySelectorAll into document.getElementsByClassName.
  3.Don't call document.getElementById("randomPizzas") every time.
  4.Don't call determineDx every time.
