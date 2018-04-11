# Chain of Responsibility Design Pattern

***
###	What is the Chain of Responsibility Design Pattern
-	This pattern sends data to an object and if that object can't use it, it sends it to any number of other objects that may be able to use it
	-	Create 4 objects that can either add, substract, multiply, or divide
	-	Send 2 numbers and a command and allow these 4 objects to decide which can handle the requested calculation

***
_Example 1_ :-  
![Chain of Responsibility Pattern](http://www.dofactory.com/images/diagrams/net/chain.gif)

***
_Example 2_ :-  
![Chain of Responsibility Pattern 2](https://cdn.journaldev.com/wp-content/uploads/2013/07/Chain-of-Responsibility-Class-Diagram.png)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/103fdf46b7d882885e0d01fe83ba29b7.js"></script>