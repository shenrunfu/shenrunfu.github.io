---
layout: post
title: How to stretch menu items evenly
published: true
---
    

When coming to style the menu bar, it usually needs to spread the menu items evenly across the window. 
There are couple of ways to do that, but each of them has its fitness and limitation to a specific circumstance.

Here is the first way shown in the first demo below. Basically it takes advantages of text align property 'justify'. 
Setting that property can make the texts fill the full space of a line and make the space between each 2 items is 
distributed evenly. It works for all lines in a paragraphs but the last one because it's been just designed for paragraphs. The trick
of how to resolve it is simulating the last line of text by utilizing :after attribute of the menu. What can we do is 
making the :after as inline element and setting its width to be 100%. Check out the CSS tab for details. 

The limitation of that is as the space between 2 items doesn't belong to any of them, so when coming to style the
background color of each items and fill out the white space around them, it's going to be hard. So this solution is good for 
spreading text menu with style on the text. 

<p data-height="150" data-theme-id="11514" data-slug-hash="ZYKpPK" data-default-tab="result" data-user="dshen" class='codepen'>See the Pen <a href='http://codepen.io/dshen/pen/ZYKpPK/'>How to stretch menus evenly</a> by DanielShen (<a href='http://codepen.io/dshen'>@dshen</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>


The other way to distribute menus items is using table. Table can nicely spread the cells evenly by using the 
fixed property of table layout. This solution probably suit most of the circumstances - it provides the most flexibility
to style every menu item. On the flip side, if you need to pull the first left item to the left edge and the far right
item to the right edge and even the gaps between the menu items, it's almost impossible, but the first method above can do that. 


<p data-height="150" data-theme-id="11514" data-slug-hash="BywNde" data-default-tab="result" data-user="dshen" class='codepen'>See the Pen <a href='http://codepen.io/dshen/pen/BywNde/'>How to stretch menu using evenly - using table</a> by DanielShen (<a href='http://codepen.io/dshen'>@dshen</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Hope you guys love this post. If you have any suggestion or comment, put it on the post comment below.