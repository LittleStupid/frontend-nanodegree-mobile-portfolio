# How to open:
  open index.html with browser.

# About html profile:
  1.move 'load css' code into foot tags
  2.delete <script src="http://www.google-analytics.com/analytics.js"></script>

# How to optimize pizza page:
1.use getElementById/getElementsByClassName instead of querySelector.
2.don't set styles every time, batch them.
3.don't call function every time if one call is enough to provide data.

### About bugs
I found the bug "pizza size is not the same" still happened in the original version.
In pizza.html, only col-md-xx is provided, I think some responsive bug will happen because
of this.
