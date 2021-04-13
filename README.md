The SOLID Principles

S - Single Responsibility 
A class should have a single responsibility. If a Class has many responsibilities, it increases the possibility of bugs because making changes to one of its responsibilities, could affect the other ones without you knowing.
The goal of this is to separate behaviors so that if something bugs it won't affect other behaviours.

O - Open-Closed
Classes should be open for extension, but closed for modification. Changing the current behaviour of a Class will affect all the systems using that Class. If you want the class to perform more functions, you want to add to the functions not change them.

L - Liskov Substitution
When a child Class cannot perform the same actions as its parent Class, this can cause bugs.If you have a Class and create another Class from it, it becomes a parent and the new Class becomes a child. The child Class should be able to do everything the parent Class can do. This process is called Inheritance.The child Class should be able to process the same requests and deliver the same result as the parent Class or it could deliver a result that is of the same type.

I - Interface Segregation
When classes are required to perform actions that aren't useful it's wasteful. A class should only perform actions that are required for its role.

D - Dependency Inversion
High-level Module(or Class): Class that executes an action with a tool.
Low-level Module (or Class): The tool that is needed to execute the action
Abstraction: Represents an interface that connects the two Classes.
Details: How the tool works
This principle says a Class should not be fused with the tool it uses to execute an action. It should fuse with the interface which will allow the tool to connect to the class.

