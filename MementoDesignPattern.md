# Memento Design Pattern

***
### What is the Memento Pattern
-	A way to store previous states of an Object easily
-	Memento : The basic object that is stored in different states
-	Originator : Sets and Gets values from the currently targeted Memento. Creates new Mementos and assigns current values to them
-	Caretaker : Holds an ArrayList that contains all previous versions of the Memento. It can store and retrieve stored Mementos

***
_Example 1_ :-  
![Memento Pattern](http://www.dofactory.com/images/diagrams/net/memento.gif)

***
_Example 2_ :-  
![Memento Pattern 2](https://www.tutorialspoint.com/design_pattern/images/memento_pattern_uml_diagram.jpg)

***
_Example 3_ :-  
![Memento Pattern 3](/assets/image/Memento3.png)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/3f1d242d40a01877cf7d7b11a6182f6f.js"></script>
