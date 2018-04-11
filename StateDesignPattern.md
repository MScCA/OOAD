# State Design Pattern

***
### What is State Pattern
-	Allows an object to alter its behaviour when its internal state changes. The object will appear to change its class.
-	Context (Account) : Maintains an instance of ConcreteState subclass that defines the current state.
-	State : Defines an interface for encapsulating the behaviour associated with a particular state of the Context.
-	Concrete State : Each subclass implements a behavior associated with the state of Context
	-	Think about all possible states for the ATM:
		-	HasCard
		-	NoCard
		-	HasPin
		-	NoCash
	-	Think about all of the different ways the user could use an ATM:
		-	InsertCard
		-	EjectCard
		-	InsertPin
		-	RequestCash

***
_Example 1_ :-  
![State Pattern](http://www.dofactory.com/images/diagrams/net/state.gif)

***
_Example 2_ :-  
![State Pattern 2](https://i.stack.imgur.com/UCMr1.png)

***
_Example 3_ :-  
![State Pattern 3](https://pic002.cnblogs.com/images/2012/358984/2012050411054690.png)

***
### Code :-
<script src="https://gist.github.com/KushalKatta/f6f404e11200174a660e18778fff993e.js"></script>