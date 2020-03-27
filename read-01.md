# Responsive Web Design
Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop. Responsive web design is focused around providing an intuitive and gratifying experience for everyone. Desktop computer and cell phone users alike all benefit from responsive websites.

## Flexible Layouts
Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media. The first part, flexible layouts, is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly percentages or em units. These relative lengths are then used to declare common grid property values such as width, margin, or padding.

## Flexible Grid
Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units. In this example we’ll use percentages but em units would work equally as well. Notice, no matter how wide the parent container becomes, the section and aside margins and widths scale proportionally.

# Media Queries
Media queries were built as an extension to media types commonly found when targeting and including styles. Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example. Being able to apply uniquely targeted styles opens up a world of opportunity and leverage to responsive web design.

# Float 
Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called "text wrap". Here is an example of that.
![img](https://i1.wp.com/css-tricks.com/wp-content/csstricks-uploads/print-layout.png?resize=540%2C270&ssl=1)

**Techniques for Clearing Floats**
* The Empty Div Method : <div style="clear: both;"></div>
* The Overflow Method : elies on setting the overflow CSS property on a parent element.
* The Easy Clearing Method :  uses a clever CSS pseudo selector (:after) to clear floats.

**CSS Floats Explained By Riding An Escalator**
Floats create alternate flows. This is the hardest part to understand. And once you introduce them, you then need to write your code so that it accounts for up to three flows: normal, left and right. This is a whole new set of rules, as opposed to manipulating the width of elements or their positioning.

# SMACSS is becoming one of the most useful contributions to front-end discussions in years
Learn how to structure your CSS to allow for flexibility and maintainability as your project and your team grows.
MACSS (pronounced “smacks”) is more style guide than rigid framework. There is no library within here for you to download or install. There is no git repository for you to clone. SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS.

## HTML5 and SMACSS
As it turns out, it works just as well with HTML5 as it does with HTML4 or any other HTML you might be using with your CSS. That is because the SMACSS approach has two core goals:

* Increase the semantic value of a section of HTML and content
* Decrease the expectation of a specific HTML structure

HTML5 introduces a number of new elements which can help us increase the semantic value of a section of HTML and content. Tags like section, header, and aside are more descriptive than a simple div. We have new input types that allow us to differentiate a numeric field from a date field from a text field. The extra tags and attributes have allowed us to be more descriptive. That is a good thing.