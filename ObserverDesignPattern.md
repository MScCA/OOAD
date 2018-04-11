# Observer Design Pattern

***
### What is an Observer Pattern
-	When you need many other object to receive an update when another object changes.
	-	Stock market with thousands of stocks needs to send updates to objects representing individual stocks
	-	The Subject (publisher) sends many stock to the Observers
	-	The Observers (subscribers) takes the ones they want and use them
-	Loose coupling is a __benefit__
	-	The Subject (publisher) doesn't need to know anything about the Observers (subscribers)
-	Negatives: The Subject (publisher) may send updates that don't matter to the Observer (subscriber)

***
_Example 1_ :-  
![Observer Pattern 1](http://www.dofactory.com/images/diagrams/net/observer.gif)

***
_Example 2_ :-  
![Observer Pattern 2](https://i.pinimg.com/564x/94/96/54/949654de0340cc1f7361e48511ab670e--class-diagram-design-patterns.jpg)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/195bf21fa999a991187cd89c495175f7.js"></script>