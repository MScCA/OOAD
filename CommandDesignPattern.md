# Command Design Pattern

***
### What is Command Design Pattern
-	The Command Pattern is a behavioural design pattern in which an object is used to represent and encapsulate all the information needed to call a method at a later time.
-	This information includes the method name, the object that owns the method and values for the method parameters.

-	Allows you to store lists of code that is executed at a later time or many times.
-	Client says I want a specific Command to run when execute() is called on 1 of these encapsulated (hidden) Objects.
-	An Object called Invoker transfers this Command to another Object called a Receiver to execute the right code
-	TurnTVOn - DeviceButton - TurnTVOn - Television.TurnTVOn()

***
_Example 1_ :-  
![Command Pattern](https://www.tutorialspoint.com/design_pattern/images/command_pattern_uml_diagram.jpg)

***
_Example 2_ :-  
![Command Pattern 2](http://www.dofactory.com/images/diagrams/net/command.gif)

***
_Example 3_ :-  
![Command Pattern 3](http://blog.lukaszewski.it/wp-content/uploads/2013/07/command_diagram.png)

***
_Example 4_ :-  
![Command Pattern 4](https://i.stack.imgur.com/ATk24.png)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/bd9f2e73e579a33ece6d1a221d37d70d.js"></script>