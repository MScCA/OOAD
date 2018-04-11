# UML Diagram

-	The elements are like components which can be associated in different ways to make a complete UML picture, which is known as diagram. Thus, it is very important to understand the different diagrams to implement the knowledge in real-life systems.

-	Any complex system is best understood by making some kind of diagrams or pictures. These diagrams have a better impact on our understanding. If we look around, we will realize that the diagrams are not a new concept but it is used widely in different forms in different industries.

-	We prepare UML diagrams to understand the system in a better and simple way. A single diagram is not enough to cover all the aspects of the system. UML defines various kinds of diagrams to cover most of the aspects of a system.

-	You can also create your own set of diagrams to meet your requirements. Diagrams are generally made in an incremental and iterative way.

-	There are two broad categories of diagrams and they are again divided into subcategories −

	-	[Structural Diagram](#structural-diagrams)
		-	[Class Diagram](#class-diagram)
		-	[Object Diagram](#object-diagram)
		-	[Component Diagram](#component-diagram)
		-	[Deployment Diagram](#deployment-diagram)
	-	[Behavioral Diagram](#behavioral-diagrams)
		-	[Use Case Diagram](#use-case-diagram)
		-	[Sequence Diagram](#sequence-diagram)
		-	[Collaboration Diagram](#collaboration-diagram)
		-	[Statechart Diagram](#statechart-diagram)
		-	[Activity Diagram](#activity-diagram)
	-	[Summary](https://www.tutorialspoint.com/uml/uml_quick_guide.htm)
***
## structural diagrams
The structural diagrams represent the static aspect of the system. These static aspects represent those parts of a diagram, which forms the main structure and are therefore stable.

These static parts are represented by classes, interfaces, objects, components, and nodes. The four structural diagrams are −
-	[Class Diagram](#class-diagram)
-	[Object Diagram](#object-diagram)
-	[Component Diagram](#component-diagram)
-	[Deployment Diagram](#deployment-diagram)

***
### class diagram

-	Class diagrams are the most common diagrams used in UML. Class diagram consists of classes, interfaces, associations, and collaboration. Class diagrams basically represent the object-oriented view of a system, which is static in nature.

-	Active class is used in a class diagram to represent the concurrency of the system.

-	Class diagram represents the object orientation of a system. Hence, it is generally used for development purpose. This is the most widely used diagram at the time of system construction.

-	[Read More](https://www.tutorialspoint.com/uml/uml_class_diagram.htm)

***
### object diagram

-	Object diagrams can be described as an instance of class diagram. Thus, these diagrams are more close to real-life scenarios where we implement a system.

-	Object diagrams are a set of objects and their relationship is just like class diagrams. They also represent the static view of the system.

-	The usage of object diagrams is similar to class diagrams but they are used to build prototype of a system from a practical perspective.

-	[Read More](https://www.tutorialspoint.com/uml/uml_object_diagram.htm)

***
### component diagram

-	Component diagrams represent a set of components and their relationships. These components consist of classes, interfaces, or collaborations. Component diagrams represent the implementation view of a system.

-	During the design phase, software artifacts (classes, interfaces, etc.) of a system are arranged in different groups depending upon their relationship. Now, these groups are known as components.

-	Finally, it can be said component diagrams are used to visualize the implementation.

-	[Read More](https://www.tutorialspoint.com/uml/uml_component_diagram.htm)

***
### deployment diagram

-	Deployment diagrams are a set of nodes and their relationships. These nodes are physical entities where the components are deployed.

-	Deployment diagrams are used for visualizing the deployment view of a system. This is generally used by the deployment team.

-	Note − If the above descriptions and usages are observed carefully then it is very clear that all the diagrams have some relationship with one another. Component diagrams are dependent upon the classes, interfaces, etc. which are part of class/object diagram. Again, the deployment diagram is dependent upon the components, which are used to make component diagrams.

-	[Read More](https://www.tutorialspoint.com/uml/uml_component_diagram.htm)

***
## behavioral diagrams

Any system can have two aspects, static and dynamic. So, a model is considered as complete when both the aspects are fully covered.

Behavioral diagrams basically capture the dynamic aspect of a system. Dynamic aspect can be further described as the changing/moving parts of a system.

UML has the following five types of behavioral diagrams −

-	[Use Case Diagram](#use-case-diagram)
-	[Sequence Diagram](#sequence-diagram)
-	[Collaboration Diagram](#collaboration-diagram)
-	[Statechart Diagram](#statechart-diagram)
-	[Activity Diagram](#activity-diagram)

***
### use case diagram

-	Use case diagrams are a set of use cases, actors, and their relationships. They represent the use case view of a system.

-	A use case represents a particular functionality of a system. Hence, use case diagram is used to describe the relationships among the functionalities and their internal/external controllers. These controllers are known as actors.

-	[Read More](https://www.tutorialspoint.com/uml/uml_use_case_diagram.htm)

***
### sequence diagram

-	A sequence diagram is an interaction diagram. From the name, it is clear that the diagram deals with some sequences, which are the sequence of messages flowing from one object to another.

-	Interaction among the components of a system is very important from implementation and execution perspective. Sequence diagram is used to visualize the sequence of calls in a system to perform a specific functionality.


-	[Read More](https://www.tutorialspoint.com/uml/uml_interaction_diagram.htm)

***
### collaboration diagram

-	Collaboration diagram is another form of interaction diagram. It represents the structural organization of a system and the messages sent/received. Structural organization consists of objects and links.

-	The purpose of collaboration diagram is similar to sequence diagram. However, the specific purpose of collaboration diagram is to visualize the organization of objects and their interaction.

-	[Read More](https://www.tutorialspoint.com/uml/uml_interaction_diagram.htm)

***
### statechart diagram

-	Any real-time system is expected to be reacted by some kind of internal/external events. These events are responsible for state change of the system.

-	Statechart diagram is used to represent the event driven state change of a system. It basically describes the state change of a class, interface, etc.

-	State chart diagram is used to visualize the reaction of a system by internal/external factors.

-	[Read More](https://www.tutorialspoint.com/uml/uml_statechart_diagram.htm)

***
### activity diagram

-	Activity diagram describes the flow of control in a system. It consists of activities and links. The flow can be sequential, concurrent, or branched.

-	Activities are nothing but the functions of a system. Numbers of activity diagrams are prepared to capture the entire flow in a system.

-	Activity diagrams are used to visualize the flow of controls in a system. This is prepared to have an idea of how the system will work when executed.

-	[Read More](https://www.tutorialspoint.com/uml/uml_activity_diagram.htm)