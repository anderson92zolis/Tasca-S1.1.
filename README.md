# Tasca-S1.1.
HTML i CSS amb Flex. In this practice you will have to make a Layout that must work both on desktop, mobile and tablet.


In this practice you will have to make a Layout that must work both on desktop, mobile and tablet.


 Important: Knowledge you must have to facilitate solving the practice.

HTML and CSS
Flexbox. -> Flexbox CSS: Complete Guide, Elements and Examples
Media queries (you can use the cut points like bootstrap. -> Media queries
Keep the following considerations in mind. These are common errors in deliveries:

In general, we never heighten a layer, but instead let the layer adapt to its content (if the layer has no content, you can heighten it).
The page should not have a horizontal scroll bar (if it happens to you, you will have to find out by inspecting the page which block is wider than the browser screen).
Inside a div there are usually other divs. divs have display:block by default. This causes them to be placed vertically. Therefore, it is often not necessary to specify the following styles for an element to be redundant:
.element{ display:flex; flex-direction:column }
In a div, by default the width is the whole of the layer it wraps, so you usually won't need to specify width:100%
