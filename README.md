# JAVA-OOP-Notes

This repository containes my personal notes on the **JAVA OOP**,**important concepts** and some ideas about the **java software engineer**, this is not a course to explain but it can be very usefull as a reminder of principles of java and Object Oriented Programming. 

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
 
    ##   the difference between lists and sets in Java?

They difference in how their items’ ordering and uniqueness.
- **Lists are ordered and allow duplicate values.**
- **Sets are unordered and do not allow duplicate elements.**
 
   ##  Process vs Threads
Process = Multiple applications running simultaneously in the server, PC or Mac

Thread =Multiple tasks running within a process

   ## Explain different ways of creating a thread. Which one i think is better
   There are three ways that can be used in order for a Thread to be created:
- A class may extend the Thread class.
- A class may implement the Runnable interface.
- An application can use the Executor framework, in order to create a thread pool.

The Runnable interface is preferred, as it does not require an object to inherit the Thread class. In case your application design
requires multiple inheritance, only interfaces can help you. Also, the thread pool is very efficient and can be implemented and
used very easily.

 ## Java concepts an entry-level junior should know:

   - Basic OOP principles
   - Abstraction, encapsulation, inheritance, polymorphism, and others.
   - SOLID principles and the way they apply to Java.
   - Knowing how to manage interfaces, classes, and objects, understand the difference between these elements.
   - A deeper knowledge of Object methods and their top applications.
   - Hierarchy of collections and exceptions.
   - Basics multithreading, understanding the concepts of threads and processes.
   - Superficial command of lambdas, streams, and functional interfaces.
  ## Java concepts an experienced junior should know:

   - Basic understanding of pile and stack
   - Speed, memory consumption, structure, the garbage collector (decent command).
   - Collections, processing null-statements using HashMap and TreeMap.
   - Handling generics, using abstract class constructors, “IS-A” inheritance.
   - Methods, wrapped classes, hash-code, equals, boxing-unboxing.
   - Basic multithreading concepts, understanding how to create a safe thread.
   - Exception handling.
   
   ##  Java concepts a confident junior should know:

   - Basic understanding of NIO and I/O.
   - Data and period handling.
   - A deeper understanding of multi-threading, handling main concurrent classes, understanding which elements the synchronization is centered around.
   - Understanding main garbage collector strategies.
   - Inheritance of exceptions.
   - Where to find info about classes and methods in runtime.
