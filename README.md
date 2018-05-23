.section
splits up the page horizontally. You'll need a few of these to break up the content, and you can use them in your main wrapper, or within other divs.

.col
divides the section into columns. Each column has a left margin except the first one. Using .col:first-child { margin-left: 0; } means you don't need to use class="last" anywhere. It works in all browsers since IE6.

.group
solves floating problems, by forcing the section to self clear its children (aka the clearfix hack). This is good in Firefox 3.5+, Safari 4+, Chrome, Opera 9+ and IE 6+.

.span_1_of_3
specifies the width of the column. Using percentages means it's 100% fluid.

@media queries
as soon as the screen size gets less than 480 pixels the columns stack and the margins disappear.