1. CSS (Cascading Style Sheets) is the language used to style an HTML document. It describes how HTML elements should be displayed on the screen.
2. To start taking control, add a style element within the head element.
3. You can add style to an element by specifying it in the style element and setting a property for it like this:
Example Code
element {
 property: value;
}
Center the content of the h1 element by setting its text-align property to the value center.
4. type selector to style element
element {
 property: value;
}
5. You can add the same group of styles to many elements by creating a list of selectors. Each selector is separated with commas like this:
Example Code
selector1, selector2 {
  property: value;
}
6. Inside the head element, add a link element. Give it a rel attribute with the value of "stylesheet" and a href attribute with the value of "styles.css".
7. For the styling of the page to look similar on mobile as it does on a desktop or laptop, you need to add a meta element with a special content attribute.
Add the following within the head element:
Example Code
<meta name="viewport" content="width=device-width, initial-scale=1.0">
8. background-color attribute to change the background-color of element
9. The div element is used mainly for design layout purposes unlike the other content elements you have used so far.
10. The goal now is to make the div not take up the entire width of the page. The CSS width property is perfect for this.
You can use the id selector to target a specific element with an id attribute. An id selector is defined by placing the hash symbol # directly in front of the element's id value. For example, if an element has the id of cat then you would target that element like this:
Example Code
#cat {
  width: 250px;
}
11. Comments in CSS look like this:
Example Code
/* comment here */
11. Next, you want to center the #menu horizontally. You can do this by setting its margin-left and margin-right properties to auto. Think of the margin as invisible space around an element. Using these two margin properties, center the #menu element within the body element.
12. A class selector is defined by a name with a dot directly in front of it, like this:
Example Code
.class-name {
  styles
}
13. add a background-image property and set its value to url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg).
14. article elements commonly contain multiple elements that have related information. In this case, it will contain a coffee flavor and a price for that flavor. 
15. To align text inside element use  text-align property and set there value of left,right or center.
16.  p elements are block-level elements, so they take up the entire width of their parent element. o get them on the same line, you need to apply some styling to the p elements so they behave more like inline elements. Using  display property with value inline-block so the p elements behave more like inline elements.
17. inline-block elements only take up the width of their content. To spread them out, add a width property to the flavor and price class selectors that have a value of 50% each. Styling the p elements as inline-block and placing them on separate lines in the code creates an extra space to the right of the first p element, causing the second one to shift to the next line. 
18. max-width property to the menu class with a value of 500px to prevent it from growing too wide.
19.  font-family property with the value sans-serif and Impact. This is a fairly common font that is very readable.
20. You can add a fallback value for the font-family by adding another font name separated by a comma. Fallbacks are used in instances where the initial is not found/available.: font-faminly:Impact,sans-serif.
21. Make the Est. 2020 text italicized by creating an established class selector and giving it the font-style property with the value italic.
22. Use the font-size property to set text value for element
23. hr element to display a divider between sections of different content.
24. height property to set the height of element
25. make all the edge of elements by using border-color property.
26. Notice how the thickness of the line looks bigger? The default value of a property named border-width is 1px for all edges of hr elements
27.  when the link has actually been visited by using a pseudo-selector that looks like a:visited { propertyName: propertyValue; }.
28. when the mouse hovers over the link by using a pseudo-selector that looks like a:hover { propertyName: propertyValue; }.
29. when the link is actually clicked by using pseudo-selectot that lonks like a:active{ propertyName: propertyValue; }.
30.  Negative values are created using a - in front of the value. 