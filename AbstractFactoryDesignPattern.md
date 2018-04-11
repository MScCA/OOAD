# Abstract Factory Design Pattern

***
### What is an Abstract Factory
-	It is like a factory, but everthing is encapsulated
	-	The method that orders the object
	-	The factories that builds the object
	-	The final objects
	-	The final objects contain objects that use the Strategy Pattern
		-	Composition: Object class fields are objects

***
### What can you do with an Abstract Factory
-	Allows you to create families of related objects without specifying a concrete class
-	Use when you have many objects that can be added, or changed, dynamically during runtime
-	You can model anything you can imagine and have those objects interact through common interfaces
-	The Bad: Things can get complicated

***
_Example 1_ :-  
![Abstract Factory 2](https://kymr.github.io/files/design-pattern/factory-pattern/abstract-factory.png)

***
_Example 2_ :-  
![Abstract Factory 3](https://kymr.github.io/files/design-pattern/factory-pattern/abstract-factory-example.png)

***
_Example 3_ :-  
![Abstract Factory 4](https://kymr.github.io/files/design-pattern/factory-pattern/abstract-factory-pizza.jpg)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/e9645ac1640e47c5c6306a0a3c6f6ba4.js"></script>

***
![Abstract Factory 5](http://www.newthinktank.com/wp-content/uploads/2012/09/Abstract-Factory-Small-300x169.png)