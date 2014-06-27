jquery.splitter
===============

[![Code Climate](https://codeclimate.com/github/nikolaifedorov/jquery.splitter.png)](https://codeclimate.com/github/nikolaifedorov/jquery.splitter)

The splitter() plugin implements a two-pane resizable splitter window.
The selected elements in the jQuery object are converted to a splitter;
each selected element should have two child elements, used for the panes
of the splitter. The plugin adds a third child element for the splitbar.

For more details see: http://methvin.com/splitter/



# Example

```javascript
$().ready(function(){
  $("#MySplitter").splitter();
});
```



# Demo

[Minimal vertical splitter](http://methvin.com/splitter/vbasic.html): Demonstrates minimal code/markup needed to create a splitter. All the styles are included in the HTML file for this example.

[Vertical splitter](http://methvin.com/splitter/vsplitter.html): Vertical splitter with fixed height and fluid width.

[Horizontal splitter](http://methvin.com/splitter/hsplitter.html): Horizontal splitter with fixed height and width.

[Another vertical splitter](http://methvin.com/splitter/vsplitter2.html): Vertical splitter with skinny splitbar and custom cursor.

[3-Pane splitter](http://methvin.com/splitter/3psplitter.html): Shows how to nest a horizontal splitter inside a vertical splitter.

[3-Column splitter](http://methvin.com/splitter/3csplitter.html): Nests vertical splitters to obtain a 3-column effect.

[4-pane splitter](http://methvin.com/splitter/4psplitter.html): Nests multiple splitters to get one vertical pane and three horizontal ones.

[Docking splitter](http://methvin.com/splitter/vsplitter-docking.html): Splitter that allows the user to double-click the splitbar to "dock" it.

# Release Notes
See the [release notes](http://methvin.com/splitter/history.html) for the changes from previous versions.

# Patch Contributors



# Lincense

Released under dual licensed under the MIT and GPL licenses:

MIT:
http://www.opensource.org/licenses/mit-license.php

GPL:
http://www.gnu.org/licenses/gpl.html

