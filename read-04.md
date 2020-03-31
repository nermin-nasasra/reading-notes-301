## RegExr
 was created by gskinner.com, and is proudly hosted by Media Temple.
Edit the Expression & Text to see matches. Roll over matches or the expression for details. PCRE & JavaScript flavors of RegEx are supported. Validate your expression with Tests mode.
The side bar includes a Cheatsheet, full Reference, and Help. You can also Save & Share with the Community, and view patterns you create or favorite in My Patterns.
Explore results with the Tools below. Replace & List output custom results. Details lists capture groups. Explain describes your expression in plain English.
Regular expressions (regex or regexp) are extremely useful in extracting information from any text by searching for one or more matches of a specific search pattern (i.e. a specific sequence of ASCII or unicode characters).

## Basic topics
* Anchors — ^ and $
* Quantifiers — * + ? and {}
* OR operator — | or []
* Character classes — \d \w \s and .

## Flags
We are learning how to construct a regex but forgetting a fundamental concept: flags.
A regex usually comes within this form /abc/, where the search pattern is delimited by two slash characters /. At the end we can specify a flag with these values (we can also combine them each other):
* g (global) does not return after the first match, restarting the subsequent searches from the end of the previous match
* m (multi-line) when enabled ^ and $ will match the start and end of a line, instead of the whole string
* i (insensitive) makes the whole expression case-insensitive (for instance /aBc/i would match AbC)

## A Complete Guide to Grid
### Grid Container
The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.
### Grid Item
The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.
### Grid Line
The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.
### Grid Track
The space between two adjacent grid lines. You can think of them like the columns or rows of the grid. Here’s the grid track between the second and third row grid lines.
### Grid Cell
The space between two adjacent row and two adjacent column grid lines. It’s a single “unit” of the grid. Here’s the grid cell between row grid lines 1 and 2, and column grid lines 2 and 3.
### Grid Area
The total space surrounded by four grid lines. A grid area may be comprised of any number of grid cells. Here’s the grid area between row grid lines 1 and 3, and column grid lines 1 and 3.

## Common Responsive Layouts with CSS Grid
CSS grid is now supported in Samsung internet v6.2 and many other modern browsers and has been the answer to many a prayer of web developers everywhere. In the same way that flexbox gave us a way to layout block elements next to each other, CSS grid lets us not only arrange elements in a row or a column, but in multiple rows and columns. Finally two dimensional layouts are becoming simpler!
