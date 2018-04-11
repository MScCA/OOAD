# Bridge Design Pattern

***
### What is Bridge Pattern
-	Decouple an abstraction from its implementation so that the two can vary independently
-	Progressively adding functionality while separating out major differences using abstract classes

***
### When to use the Bridge Pattern
-	When you want to be able to change both the abstraction (abstract classes) and concrete classes independently
-	When you want the first abstract class to define rules (Abstract TV)
-	The concrete class adds additional rules (Concrete TV)
-	An abstract class has a reference to the device and it defines abstract methods that will be defined (Abstract Remote)
-	The Concrete Remote defines the abstract methods required

***
_Example 1_ :-  
![Bridge Pattern](http://www.dofactory.com/images/diagrams/net/bridge.gif)

***
_Example 2_ :-  
![Bridge Pattern 2](https://cdn.journaldev.com/wp-content/uploads/2013/07/bridge-design-pattern.png)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/820bfcbf8a3d9add8cde9d1e73a8dd9a.js"></script>