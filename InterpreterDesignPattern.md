# Interpreter Design Pattern

***
### What is the Interpreter Design Pattern
-	It is used to convert one represntation of data into another
-	The Context contains the information that will be interpreted
-	The Expression is an abstract class that defines all the methods needed to perform the different conversions
-	The Terminal or Concrete Expressions provide specific conversions on different types of data

***
_Example 1_ :-  
![Interpreter Pattern](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Interpreter_UML_class_diagram.svg/536px-Interpreter_UML_class_diagram.svg.png)

***
_Example 2_ :-  
![Interpreter Pattern 2](https://cdn.journaldev.com/wp-content/uploads/2013/07/interpreter-pattern-java.png)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/8171a068093bb56ae7336a6630b0dfbf.js"></script>