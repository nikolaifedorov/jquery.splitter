# Getting Started

Here's a quick tour on using the plugin. Markup for a vertical splitter looks like this:
```html
 <div id="MySplitter">
   <div> Left content goes here </div>
   <div> Right content goes here </div>
 </div>
```

Define a few style rules to define the splitter size and make sure the splitbar is visible:
```css
#MySplitter {
	height: 200px;
	width: 500px;
	border: 5px solid #aaa;
}
#MySplitter div {
	overflow: auto;
}
.vsplitbar {
	width: 5px;
	background: #aaa;
}
```

The top-level div has two child divs for the left and right panes. (In a horizontal splitter, the first pane is the top and the second is the bottom.) The plugin dynamically adds a splitbar that goes between the panes. To create the splitter, put a line of code in a .ready() handler to select the MySplitter div in a jQuery object and pass it to the splitter plugin:
``` javascript
 $().ready(function(){
   $("#MySplitter").splitter();
 });
```

Congratulations, there's a vertical splitter in your document!
