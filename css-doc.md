
# Ultimate CSS Grid & Layout Techniques, v3 | Frontend Masters

### CSS NOTES


**Grid Layout Exercise**


[00:01:07](https://frontendmasters.com/courses/css-grid/grid-layout-exercise?t=67)
In counting the row and columns  numbers in grid, there will always be one more than the number of columns bcos its the lines that divide them.
with columns we are specifying the width and with row we are specifying heights.
To make the grid item display default back use display block to override the grid


[00:03:41](https://frontendmasters.com/courses/css-grid/media-queries-with-grid-exercise?t=221)
Media Queries:Use desktop first for main nav and for other part of the page we may use mobile first. when you use display block to turn off grid you will also loose the gap value.


[00:00:30](https://frontendmasters.com/courses/css-grid/three-column-card-layout-exercise?t=30)
You can continue working in the CodePen from the [Chapter 7 page](https://grid-flexbox.css.education/ch7.html)

### Overlapping Cells & Subgrid

**Overlapping Rows & Columns**

[00:01:15](https://frontendmasters.com/courses/css-grid/overlapping-rows-columns?t=75)
when doing grid-template-columns, you should counts the highest columns.


**Grid Margin**


[00:04:24](https://frontendmasters.com/courses/css-grid/grid-margin?t=264)
Margin cell for paragraph(not only paragraph ) collapse normally but with grid they do not collapse bcos the grid gap will be in between the paragraph.
If you are looking at the layout and some things are weird vertically think about margin.

**minmax, auto-fit, & auto-fill**

[00:00:01](https://frontendmasters.com/courses/css-grid/subgrid?t=1)
Minmax, auto fill and fit will help to wrap grid items across the browser like the flex box wrap. In short, auto-fit will expand the grid items to fill the available space. While auto-fill won’t expand the items. Instead, auto-fill will keep the available space reserved without altering the grid items width.


### Flexbox

**Where to use Flexbox**

[00:00:06](https://frontendmasters.com/courses/css-grid/where-to-use-flexbox?t=6)
Here's a link to [Chapter 11](https://grid-flexbox.css.education/ch11.html)


**flex-direction & flex-wrap**

[00:00:14](https://frontendmasters.com/courses/css-grid/flex-direction-flex-wrap?t=14)
Here's a link to the [Flexbox properties demo](https://codepen.io/jen4web/pen/oNOwjNx)

**justify-content & align-items**

[00:01:31](https://frontendmasters.com/courses/css-grid/justify-content-align-items?t=91)
for justify-content and align-items, the main axis dictated with flex-direction is the one that you are specifying justify or align on. also flex-basis uses the main-axis


### Responsive Images


**srcset & sizes Attributes**

[00:05:10](https://frontendmasters.com/courses/css-grid/srcset-sizes-attributes?t=310)
With a base font size of 16px, 36em would equal 576 pixels



### Container Queries


**Card Page Layout**
[00:00:09](https://frontendmasters.com/courses/css-grid/wrapping-up?t=9)
Container queries  enables you to apply styles to elements nested within a specific container based on the features of that container. Width media queries consider the viewport width and container size queries consider the container width.



# Practical CSS Layouts | Frontend Masters


**Styleguide Exercise: CSS Basics Setup**

[00:09:39](https://frontendmasters.com/courses/css-layouts/styleguide-exercise-css-basics-setup?t=579)
Selectors: We write them from left to right but we read them from right to left.

[00:13:04](https://frontendmasters.com/courses/css-layouts/styleguide-exercise-css-basics-setup?t=784)
See [<hex-color> on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/hex-color) for more information

**rem vs. em Units**

[00:02:35](https://frontendmasters.com/courses/css-layouts/rem-vs-em-units?t=155)
`em` is actually "my parent element's font-size"

**Style Guide Type Sizes**

[00:00:17](https://frontendmasters.com/courses/css-layouts/style-guide-type-sizes?t=17)
Here's a link to [Advanced CSS Layouts](https://frontendmasters.com/courses/advanced-css-layouts/)

[00:00:30](https://frontendmasters.com/courses/css-layouts/style-guide-type-sizes?t=30)
Here's a link to [TypeScale](https://typescale.com/)

**Custom Font & Responsive Image**

[00:04:22](https://frontendmasters.com/courses/css-layouts/custom-font-responsive-image?t=262)
Here's a link to [Google Fonts](https://fonts.google.com/)

[00:10:03](https://frontendmasters.com/courses/css-layouts/custom-font-responsive-image?t=603)
Images size are the size that they are by default, hack is width:100% and max-width:100%


**HTML Markup for a Simple Website**

[00:09:29](https://frontendmasters.com/courses/css-layouts/html-markup-for-a-simple-website?t=569)
Main tag mean the main focus of the web page, h1 means most important of the website desrve the most important h1

[00:10:29](https://frontendmasters.com/courses/css-layouts/html-markup-for-a-simple-website?t=629)
Address tag is use for 2 situation only
- The author of an article, their contact information 
- The contact for the entire website.


**CSS for a Simple Responsive Layout**


[00:04:47](https://frontendmasters.com/courses/css-layouts/css-for-a-simple-responsive-layout?t=287)
Always put a border when you cannot see your style, if you cannot see it, you caannot style it.

**Mobile Tour Styles**

[00:07:00](https://frontendmasters.com/courses/css-layouts/mobile-tour-styles?t=420)
You can add h1 class to a h3 element. accessiblity and design

**Reviews & Images Styles**

[00:05:11](https://frontendmasters.com/courses/css-layouts/reviews-images-styles?t=311)
Images are inline by default so if show up next to each other you do not need to flex them jst reducing width.

**Margin Collapse**

[00:01:19](https://frontendmasters.com/courses/css-layouts/margin-collapse?t=79)
vertical margins collapse in css and the larger size wins.The top and bottom margins of blocks are sometimes combined (collapsed) into a single margin whose size is the largest of the individual margins (or just one of them, if they are equal), a behavior known as margin collapsing. Note that the margins of floating and absolutely positioned elements never collapse.
padding is alaways addictive

**CSS for Tablet Layout**

[00:05:34](https://frontendmasters.com/courses/css-layouts/css-for-tablet-layout?t=334)
min-width media query is mobile first while max-width is desktop first.

[00:07:14](https://frontendmasters.com/courses/css-layouts/css-for-tablet-layout?t=434)
Here are the [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/)

**Responsive Images with the Picture Element**

[00:04:33](https://frontendmasters.com/courses/css-layouts/responsive-images-with-the-picture-element?t=273)
<picture> element is a way to add more than one image responsive

**Basic Tablet CSS Layout**

[00:08:29](https://frontendmasters.com/courses/css-layouts/basic-tablet-css-layout?t=509)
add border to grid children so you can see and count the start and end         /* grid-row-start / grid-column-start / grid-row-end / grid-column-end */
      grid-area: 1/1/2/4;
you might not need the gap property. use border first
the counting of the row start and all will be on the desired design
when assigning the children items to the specific area, focusing on the item that occupy all the area will make grid specify the other items for us


**Tour Page Styles**

[00:06:16](https://frontendmasters.com/courses/css-layouts/tour-page-styles?t=376)
use button for anything that has to do with JS or not a link. use anchor tag for everything that a link. if the <a> tag has to go somewhere but did not e.g button sold out, use a tag without the href and style it like a button


[00:11:08](https://frontendmasters.com/courses/css-layouts/tour-page-styles?t=668)
`linear-gradient(180deg, var(--black) 0%, var(--teal) 100%);

**Button Interactive States**

[00:00:15](https://frontendmasters.com/courses/css-layouts/button-interactive-states?t=15)
Adding a width to buttons will make them all have same size

[00:04:17](https://frontendmasters.com/courses/css-layouts/button-interactive-states?t=257)
Here's a link to [How to Draw Diagonal Line with CSS](https://codepen.io/jen4web/pen/oNaYexj)

[00:08:03](https://frontendmasters.com/courses/css-layouts/button-interactive-states?t=483)
pointer-events:none and you will not need to change the border color etc state

[00:08:03](https://frontendmasters.com/courses/css-layouts/button-interactive-states?t=483)
use linear gradients to draw a cross line

**Tour Text Styles**

[00:03:48](https://frontendmasters.com/courses/css-layouts/tour-text-styles?t=228)
Check out support for `:has` on [caniuse.com](https://caniuse.com/?search=%3Ahas)

[00:04:20](https://frontendmasters.com/courses/css-layouts/tour-text-styles?t=260)
the :has selector will look into the parent if the condition is true

[00:04:28](https://frontendmasters.com/courses/css-layouts/tour-text-styles?t=268)
if you use img tag to display svg, it is means you cannot get a  hover state on it. will have to use svg included here without the img tag


**Reviews & Images Mobile Styles**

[00:02:48](https://frontendmasters.com/courses/css-layouts/reviews-images-mobile-styles?t=168)
Aside element is an secondary/support content to your main content

**Reviews & Images Tablet Styles**

[00:00:07](https://frontendmasters.com/courses/css-layouts/reviews-images-tablet-styles?t=7)
when styling, if you put margin: 0 auto and did not center you can add border to see the default space the element is taking by default. you can also check your browser to see if the element is inline or block.

[00:02:51](https://frontendmasters.com/courses/css-layouts/reviews-images-tablet-styles?t=171)
When you have to move  elements around, use order instead of rearragin them from HTML, Also, if you have grid blowout, the grid container/area will include and accommdate those outside space

[00:06:47](https://frontendmasters.com/courses/css-layouts/reviews-images-tablet-styles?t=407)
Grid blowout is when the children items move out of the grid parent. we will work with a fixed width for the grid coulmn instead of using fraction bcos fraction is flexible and will amke sure all items are inside the grid container not blow out. span allows the three image in the middle flow side by side rather than the grid start and end

**Reviews & Images Desktop Styles**

[00:09:09](https://frontendmasters.com/courses/css-layouts/reviews-images-desktop-styles?t=549)
using nth-of-type or any other type, you can make use of (an + b) formular to select your items or use n for all the items.
Relative positioning will allow you to move the item around while preserving the actual space, other content will not be adjusted to fit into any gap left. while the absolute positioning will pull the item out of the normal flow.absolute positioned elements are removed from the normal flow and can overlap elements.


**Play & Mute Button Styles**

[00:02:16](https://frontendmasters.com/courses/css-layouts/play-mute-button-styles?t=136)
Navigation is a list of unordered list bcos the link can be visited in no order hence why we should have list inside the unordered tag. For hamburger we can use the unicode of "\2630" instead of the svg or image


**Hamburger Menu Styles Exercise**

[00:14:40](https://frontendmasters.com/courses/css-layouts/hamburger-menu-styles-exercise?t=880)
Max width is also useful for content to stay at the right sizes on big screens

[00:04:11](https://frontendmasters.com/courses/css-layouts/review-layout-exercise?t=251)
We can omit the alt text of a decorative elements, when they are separators we do not need a screen reader to tell us their description.

**Double Border Corners**

[00:04:29](https://frontendmasters.com/courses/css-layouts/double-border-corners?t=269)
Every Html element has a box model around them and the contend(node) has a space around them, we can access the space using the before and the after. you have to use the content for it to work, you can use attr(), url(), text, in the content. see what is happening with the content if you did not add text with width and height.

**Social Icons**

[00:09:13](https://frontendmasters.com/courses/css-layouts/social-icons?t=553)
Grid cells are allow to overlap, so if we have two grid cell and we call out for same location, they will seat very happily on top of each other. i.e they should have same grid-column and grid-row. Grid does not really wants you to have things on top of each other by default, so we need to specify the column.

### Difficult Design: Advanced Styles

[00:03:33](https://frontendmasters.com/courses/css-layouts/tracklist-grid-for-tablet-desktop?t=213)
Grid-template-columns can be utilized to dictates the width of the items base on the space they are taking instead of fr, you can use px and add max-width to the grid parent.
You can rotate the direction of the text using tranform:rotate.

**Diamond Images Mobile Layout**

[00:02:18](https://frontendmasters.com/courses/css-layouts/diamond-images-mobile-layout?t=138)
cover tells the browser to make sure the image always covers the entire container, even if it has to stretch the image or cut a little bit off one of the edges. contain, on the other hand, says to always show the whole image, even if that leaves a little space to the sides or bottom.

The default keyword — auto — tells the browser to automatically calculate the size based on the actual size of the image and the aspect ratio.

[00:05:29](https://frontendmasters.com/courses/css-layouts/diamond-images-mobile-layout?t=329)
set a variable using --nameofvariable:valueofvariable. access it via var() function. Variables can be local or global scope. If you declare a variable in a container are scoped to the items inside the container or the container itself. variables use in the root are glocal ones.

[00:08:21](https://frontendmasters.com/courses/css-layouts/diamond-images-mobile-layout?t=501)
Note: The overflow property only works for block elements with a specified height. Note: In OS X Lion (on Mac), scrollbars are hidden by default and only shown when being used (even though "overflow:scroll" is set).

**Diamond Images Tablet & Desktop Layout**

[00:01:13](https://frontendmasters.com/courses/css-layouts/diamond-images-tablet-desktop-layout?t=73)
Sass variables are all compiled away by Sass. CSS variables are included in the CSS output.CSS variables can have different values for different elements, but Sass variables only have one value at a time.Sass variables are imperative, which means if you use a variable and then change its value, the earlier use will stay the same. CSS variables are declarative, which means if you change the value, it’ll affect both earlier uses and later uses. you can change css variable at the media query



# Intermediate HTML & CSS | Frontend Masters

**HTML Elements Q&A**

[00:00:06](https://frontendmasters.com/courses/intermediate-html-css/html-elements-q-a?t=6)
HTML identifies the elements of the webpage and is not responsible for the display of the page. comes with hidden treasures of accessibility, SEO and AI. think about content of the website you must think about html. we have 112 elements. Semantic elements = elements with a meaning. , we have non semantics tag e.g div and span. sematic element is good bcos the browser has some default styling associated to it by default. right accessibility with it.

**HTML Lists**

[00:02:38](https://frontendmasters.com/courses/intermediate-html-css/html-lists?t=158)
[semantics-selectors.css.education](https://semantics-selectors.css.education/)

[00:02:38](https://frontendmasters.com/courses/intermediate-html-css/html-lists?t=158)
There are four kinds of list in HTML. Unordered, Ordered, Formerly defination and interactive lists


[00:08:07](https://frontendmasters.com/courses/intermediate-html-css/html-lists?t=487)
Ordered list are use for ranking and the numbers are significant, they come with some attributes e.g reversed, start, type{from html} that turn the number around. they communicate meaning when use from html. 
Nested list has to be inside the <li> nested list</li> list

**Attribute Selectors**

[00:00:47](https://frontendmasters.com/courses/intermediate-html-css/attribute-selectors?t=47)
Attributes selector can be useful when styling form a[target]. ^(start) $(end) *{contain} are called arbitrary substring attribute value


**Styling List Item Markers**

[00:02:32](https://frontendmasters.com/courses/intermediate-html-css/styling-list-item-markers?t=152)
emoji for list-style is command control and space;

[00:05:27](https://frontendmasters.com/courses/intermediate-html-css/styling-list-item-markers?t=327)
[fontawesome.com](https://fontawesome.com)

**Description Lists & Flexbox**

[00:05:51](https://frontendmasters.com/courses/intermediate-html-css/description-lists-flexbox?t=351)
The description or definition list can be group using div but it must be after DD and DT element. content that has pairs and type of pairs e.g FAQ, if you have a relationship between two items and want to show the relation between two items, this is the great way to show it.

### Pseudo-Classes

[00:12:11](https://frontendmasters.com/courses/intermediate-html-css/level-4-pseudo-class-selectors?t=731)
Pseudo Classes [on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)

### Inheritance

**What Inherits in CSS**

[00:01:54](https://frontendmasters.com/courses/intermediate-html-css/what-inherits-in-css?t=114)
Cascades govern how the inheritance and specificity happen in cascade. Cascades deal with how are styles combined by the browser when they come from difft sources. sources like the user style sheet, browser style sheet and the author can be (external sheet, embedded sheet, inline sheet).

[00:05:20](https://frontendmasters.com/courses/intermediate-html-css/what-inherits-in-css?t=320)
In inheritance they are some properties that inherits and some that are not inherent. inherits properties are (fonts, lists, texts, space, visibility, border-collapse) not inherit(padding,margin,borders,display,positioning ,floats,background etc) all the not inherits properties deal with the box model. 
we can use the inherit property on the child element to access a property on the direct parent child relationship not grand parent.
turn off inheritance,


**CSS Specificity Overview**

[00:06:31](https://frontendmasters.com/courses/intermediate-html-css/css-specificity-overview?t=391)
[specifishity.com](https://www.specifishity.com/)



**Understanding the Cascade**

[00:00:08](https://frontendmasters.com/courses/intermediate-html-css/understanding-the-cascade?t=8)
Anything that has to do with animation will actually take priority even over the most specific. :first-line is a pseudo elements.

**Cascade Overview**

[00:00:52](https://frontendmasters.com/courses/intermediate-html-css/cascade-overview?t=52)
Cascade deal with Relevance(i.e media query, @support and layers), Origin and importance(is the style coming from user, browser, author and does it has importance before it),Specificity(Sort the styles based on the 0-0-0 formula and inheritance) and Order of appearance(i.e which ever comes later wins)

[00:05:03](https://frontendmasters.com/courses/intermediate-html-css/cascade-overview?t=303)
Cascade algorithm is applied before the Specificity algorithm. The reason we have animation that starts with @keyframe over the user agent, user and author styles is bcos we do not want the the specificity etc to get in the way of an animation that is executing as things are changing. for !important the user agent important takes prominence and only css transitions can override this value. 


The cascade is in ascending order, animations > normal values, !important >animations, transitions >!important



# CSS Projects | Frontend Masters

### Introduction

**Introduction**

[00:00:10](https://frontendmasters.com/courses/css-projects/introduction?t=10)
Here's a link to the [course website](https://projects.css.education/)

[00:04:14](https://frontendmasters.com/courses/css-projects/introduction?t=254)
Here's a link to check out Jen's [Advanced CSS Layouts](https://frontendmasters.com/courses/advanced-css-layouts/) course on Frontend Masters

[00:04:41](https://frontendmasters.com/courses/css-projects/introduction?t=281)
Here's a link to check out [Dribbble](https://dribbble.com/)

### Style Guide Project

**Style Guide Overview**

[00:00:07](https://frontendmasters.com/courses/css-projects/style-guide-overview?t=7)
Here's a link to the [course website](https://projects.css.education/)

[00:06:36](https://frontendmasters.com/courses/css-projects/style-guide-overview?t=396)
Here's a link to the [Style Guide's Beginning CodePen](https://codepen.io/jen4web/pen/yLQddYV)

[00:07:27](https://frontendmasters.com/courses/css-projects/style-guide-overview?t=447)
Here's a link to check out MDN's documentation on the [figure element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure)

[00:08:38](https://frontendmasters.com/courses/css-projects/style-guide-overview?t=518)
Here's a link to check out MDN's documentation on [CSS variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)

[00:08:52](https://frontendmasters.com/courses/css-projects/style-guide-overview?t=532)
Here's a link to check out [Jen's courses](https://frontendmasters.com/teachers/jen-kramer/)

[00:09:04](https://frontendmasters.com/courses/css-projects/style-guide-overview?t=544)
Here's a link to the [Font Scale CodePen](https://codepen.io/jen4web/pen/KKGpKBM)

**Style Guide: Fonts & Font Sizes**

[00:04:04](https://frontendmasters.com/courses/css-projects/style-guide-fonts-font-sizes?t=244)
Line-height:You should always specify line-height as a unitless number (say this into the mirror five times). That way descendent elements that specify a different font size will inherit that number instead of a fixed line height.

[00:11:12](https://frontendmasters.com/courses/css-projects/style-guide-fonts-font-sizes?t=672)
Here's a link to check out [Intermediate HTML and CSS](https://frontendmasters.com/courses/intermediate-html-css/)

**Style Guide: Image & Links**

[00:02:28](https://frontendmasters.com/courses/css-projects/style-guide-image-links?t=148)
Max-width is based on the images property not the elements properties

[00:06:39](https://frontendmasters.com/courses/css-projects/style-guide-image-links?t=399)
Figure,body,list elements has a default margin from the browser. Link(a) element has a blue color by default

**Style Guide: Colors**

[00:00:07](https://frontendmasters.com/courses/css-projects/style-guide-colors?t=7)
Here's a link to the [low highlight article](https://shannonpayne.com.au/how-to-create-a-low-highlight-text-effect-using-css/)

[00:05:40](https://frontendmasters.com/courses/css-projects/style-guide-colors?t=340)
If you have divs or other elements and you want to place them near each other like flex, you can always make use of inline-block instead of grid or flex.

### Columns & Cover Project

**Column & Cover: Media Queries**

[00:14:06](https://frontendmasters.com/courses/css-projects/column-cover-media-queries?t=846)
Here are links to [object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit) and [object-position](https://developer.mozilla.org/en-US/docs/Web/CSS/object-position)

**Background & Overflow: Mobile Layout**

[00:07:15](https://frontendmasters.com/courses/css-projects/background-overflow-mobile-layout?t=435)
Anything we hide by display none is still been loaded be the browser but not been display. you should only come up with a solution that help you load only the information you need at the moment. but css and html cannot achieve this.

**Background & Overflow: Scrollbar**

[00:02:07](https://frontendmasters.com/courses/css-projects/background-overflow-scrollbar?t=127)
Here's a link to check out [Custom Scrollbars In CSS](https://ishadeed.com/article/custom-scrollbars-css/)

