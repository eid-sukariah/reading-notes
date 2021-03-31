# Refactoring
**functional programming***
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

![#](https://miro.medium.com/max/700/1*z8UmKXwNQ65H11zMkzRs1w.jpeg)

pure functions
- It returns the same result if given the same arguments 
- It does not cause any observable side effects

Higher-order functions
**Filter**
Given a collection, we want to filter by an attribute. The filter function expects a true or false value to determine if the element should or should not be included in the result collection. Basically, if the callback expression is true, the filter function will include the element in the result collection. Otherwise, it will not.

**Map**
The idea of map is to transform a collection. The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.

**Reduce**
The idea of reduce is to receive a function and a collection, and return a value created by combining the items.
