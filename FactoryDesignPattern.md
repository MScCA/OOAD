# Factory Design Pattern

***
### What is Factory Pattern
-	When a method returns one of several possible classes that shares a common super class
	-	Create a new enemy in a game
	-	Random number generated picks a number assigned to a specific enemy
	-	The factory returns the enemy associated with that number
-	The class is chosen at run time
-	When you don't know ahead of time what class object you need
-	When all of the potential classes are in the same subclass hierarchy
-	To centralize class selection code
-	When you don't want the user to have to know every subclass
-	To encapsulate object creation

***
_Example 1_ :-  
![Factory Pattern](https://static.dzone.com/dz1/dz-files/factory_pattern_0.PNG)

***
_Example 2_ :-  
![Factory Pattern 2](https://i.ytimg.com/vi/EdIwFK0gCm4/maxresdefault.jpg)

***
_Example 3_ :-  
![Factory Pattern 3](https://www.safaribooksonline.com/library/view/head-first-design/0596007124/figs/web/136fig01.png.jpg)

***
_Example 4_ :-  
![Factory Pattern 4](https://kymr.github.io/files/design-pattern/factory-pattern/simple-factory.jpg)

***
_Example 5_ :-  
![Factory Pattern 5](https://kymr.github.io/files/design-pattern/factory-pattern/factory-method-pizza.jpg)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/c6f9fe03fdbafbc91fdd89bbf77a0d75.js"></script>

***
![Factory Pattern 6](/assets/image/Factory6.png)