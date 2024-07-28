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
15. To align text inside element use  text-align property and set there value of left,right or scebter.
