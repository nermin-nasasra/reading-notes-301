### TOPIC NAME
Concepts of Functional Programming in Javascript
 Those concepts are big advantages to build side-effect-free functions, so it is easier to maintain systems — with some other benefits.

 Pure functions benefits
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:
* Given a parameter A → expect the function to return value B
* Given a parameter C → expect the function to return value D

Functions as first-class entities can:
* refer to it from constants and variables
* pass it as a parameter to other functions
* return it as result from other functions
The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior.

### Map
The idea of map is to transform a collection.
The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.
Let’s get the same people collection above. We don't want to filter by “over age” now. We just want a list of strings, something like TK is 26 years old. So the final string might be :name is age years old where :name and :age are attributes from each element in the people collection.

