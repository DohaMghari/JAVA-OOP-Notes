# JAVA-OOP-Notes

This repository containes my personal notes on the **JAVA OOP** , this is not a course to explain but it can be very usefull as a reminder of principles of java and Object Oriented Programming. 

## OOP
Object-oriented programming contains many significant features, such as **encapsulation, inheritance, polymorphism and abstraction**
- #### Encapsulation  
  Encapsulation provides objects with the ability to hide their internal characteristics and behavior.
   <p>Some of the advantages of using encapsulation are listed below:</p>
   
  -  The internal state of every objected is protected by hiding its attributes.
  -  It increases usability and maintenance of code, because the behavior of an object can be independently changed or extended.
  -  It improves modularity by preventing objects to interact with each other, in an undesired way


- #### inheritance
  Inheritance provides an object with the ability to acquire the fields and methods of another class, called base class. Inheritance
  provides **re-usability of code** and can be used to add additional features to an existing class, without modifying it.
- #### polymorphism
   polymorphism allows you to define one interface and have multiple implementations
   - exemple :  A person at the same time can have different characteristic. Like a man at the same time is a father, a husband, an employee. So the same person posses different behaviour in different situations. 

- #### abstraction
    Abstraction is the process of separating ideas from specific instances and thus, develop classes in terms of their own functionality,
    instead of their implementation details.
    The abstraction technique aims to **separate the implementation details of a class from its behavior.**
    
## Overriding and Overloading in Java

- ### overloading : 
    Method overloading in Java occurs when two or more methods in the same class have the exact same name, but different
    parameters.
- ### overriding : 
    Method overridings defined as the case when a child class **redefines the same method as a parent class**,Overridden methods must have **the same name, argument list, and return type.**
   ##  the difference between an Interface and an Abstract class
 - All methods **in an interface are implicitly abstract**. On the other hand, **an abstract class may contain both abstract and nonabstract methods**.
 - A class may implement a number of Interfaces, but can extend only one abstract class.
 - Abstract classes can implement interfaces without even providing the implementation of interface methods.
 - Variables declared in a Java interface is by default final. An abstract class may contain non-final variables

 
