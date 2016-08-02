# Hiccups
JavaScript trivia for new JavaScript programmers.

### The Object-Oriented inheritance mechanism of JavaScript is *prototype-based*.
### **All** numbers in Javascript are represened as *floating-point values*.
### Special Numeric Constants in Javascript:
  * ```NaN``` (Not a number).
  * ```Number.POSITIVE_INFINITY```
  * ```Number.NEGATIVE_INFINITY```
  * ```Number.MAX_VALUE```
  * ```Number.MIN_VALUE``` 
 
### Function Definitions:
When you define a function in JavaScript, you create a function object that can be accessed through a variable with that function's name. There are several ways of declaring a function.
```
function square(x) {return x*x}
```
This definition is very C-like, but consider the following:
```
var square = function(x){return x*x}
```
In this second declaration, we can see an unnamed function represented as the literal data value *square* within a program.
### The null value is a value that represents *no object*.
### The null value vs the undefined value:
Null is a value that represents no object, while undefined is for any undefined value (an un-initialized member to a class, for example.) They are not the same, and we must be careful about how we compare these two values. This comparison will return true:
```null == undefined value```.
But this comparison will return false:
```null === undefined value```.
