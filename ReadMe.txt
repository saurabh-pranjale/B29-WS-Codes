CSS position property determines how an element is positioned within its parent container. There are four main values:

Static: This is the default value. Elements are positioned in the normal flow of the document.


Relative: Element is positioned relative to its normal position. It can be shifted using top, bottom, left, and right properties.

Absolute: Element is positioned relative to its nearest positioned ancestor (an ancestor with a position other than static), or to the initial containing block if there is no positioned ancestor. It won't affect the position of other elements.


Fixed: Element is positioned relative to the viewport (browser window), so it stays fixed even when the page is scrolled.
Sticky: Acts like a combination of relative and fixed. It is positioned relative to its normal position until a specified scroll point is reached, then it is "stuck" in place.