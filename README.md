# Java-Learnings
Learning Basics of Java

# Basics of Java

     1. JVM and JDK
     
     Putting it all together: Imagine you're a developer creating a Java application. 
     You use the JDK (toolbox) to write and compile your code. Once your application is 
     compiled into bytecode, it can be executed on any system with the JRE (reading lamp and chair),
     which includes the JVM (translator) to run your application smoothly across different platforms.
![image](https://github.com/RAHULRNAIR2000/Java-Learnings/assets/83546515/884e8831-7a31-4b16-80f6-39b307ce4737)

# JVM ARCHITECTURE

![jvm-architecture](https://github.com/user-attachments/assets/d3a442b7-5430-4f2b-8a5f-70fb0191de3b)

- JVM: The "engine" that runs Java programs.
- JRE: The "runtime environment" containing the JVM and libraries for running Java programs.
- JDK: The "development toolkit" containing the JRE and tools for writing and compiling Java programs.  

Think of the JRE as the "kitchen" that contains the stove (JVM) and the tools (libraries) needed to cook (run) a Java program.

     2. Structure of a Java file
     3. i/o in Java
     4. Datatypes
     5. Conditions/Loops/Switch
     6. Functions
     7. Array/ArrayList
     8. Var args
     9. Overloading
     
     10. overriding
     
         Method overriding occurs when a subclass provides a specific 
         implementation of a method that is already provided by its 
     superclass. In real life, think of a parent's rule being modified by 
     the child. For instance, a parent may have a rule to come home by 10 
         PM, but the child overrides it to come home by 11 PM.
     
# Concepts of object-oriented programming in Java

     1. Class, objects
     2. Constructors
     3. Packages
     4. Acess modifiers
     5. Inheritance, Types of inheritance
     
          Inheritance is a mechanism in Java where a new class is derived from
          an existing class (superclass). The derived class inherits the members (fields and methods) of the superclass. 
          In real life, think of inheritance as a parent passing on genetic traits to their child.
          The child inherits characteristics from the parent, like eye color or height.
          Use the keyword "extends" to use the methods and variables of the parent class.

          Types

          Single inheritance
          Multilevel inheritance
          Hierarchical inheritance
          
          Hybrid inheritance - Not in Java
          Multiple inheritance is not in Java (for that we use interfaces)

          
          
          
     6. Polymorphism

          Polymorphism is the ability of an object to take on multiple forms. 
          In Java, it can be achieved through method overloading and
          method overriding. In real life, think of a person 
          who can have multiple roles - a teacher during the day,
          a parent in the evening, and a musician during weekends.
     
     7. Abstraction/Abstract Methods
     
          Abstraction is the concept of hiding the implementation details and
          showing only the essential features of an object. In real life, think 
          of a car dashboard. When you drive a car, you only interact with the
          dashboard (like a speedometer or fuel gauge), not the internal combustion engine
          or the complex mechanics. Similarly, in programming, abstraction allows you 
          to focus on what an object does rather than how it does it.
          An abstract class cannot have objects.i should be extended to other class and 
          create an object of that class.


     
     8. Interface
     
          interface is a blueprint of a class
          It cannot have fields (variables) or constructors.
          An interface is a fully abstract class (in Java versions before 8).
          It contains only method declarations (by default) and no implementations.
          
          ## Key Differences: Abstract Class vs Interface

| Feature         | Abstract Class                              | Interface                                      |
|-----------------|---------------------------------------------|------------------------------------------------|
| **Usage**       | Use when sharing code between classes.      | Use for full abstraction (behavior specification). |
| **Methods**     | Can have abstract and concrete methods.     | Only abstract methods (before Java 8).         |
| **Constructors**| Can have constructors.                      | Cannot have constructors.                      |
| **Inheritance** | Single inheritance allowed.                 | Multiple inheritance allowed.                  |
| **Default Methods** | Available since Java 8.                 | Available since Java 8.     


     9. Enums
     10. Vector
     11. Encapsulation

     Encapsulation is one of the fundamental principles of object-oriented programming (OOP) in Java. It refers to the practice of bundling the data (fields/variables) and 
     methods that operate on that data into a single unit, typically a class, and restricting direct access to some of the object's components. This is achieved using 
     access modifiers and is often referred to as data-hiding.

     12.Generics

                Generics in Java are a mechanism that allows you to write classes, interfaces, and methods 
                that can operate on types specified as parameters. 
                This provides type safety and eliminates the need for casting in many cases

     Collections in java
     
          1. List
          
           List is an interface in Java, which means it cannot be instantiated directly. It represents an ordered collection, also known as a sequence. Lists can contain 
           duplicate elements and preserve the order of insertion.

           Common Implementations of List:

            ArrayList

            ArrayList is a resizable array implementation of the List interface. It provides more flexibility compared to a standard array by allowing dynamic resizing.
            Key Points:

            Implements the List interface.
            Allows dynamic resizing.
            Provides fast access to elements (random access)

            
            LinkedList
            
            A LinkedList consists of nodes where each node contains a reference to the previous and next node.
            This structure allows for efficient insertions and deletions as elements are not shifted when modified
            Access Time: Slower compared to ArrayList because it requires traversal from the head (or tail) to the desired index.

            ArrayList: Preferred when frequent access to elements by an index is required, and insertion/deletion operations are less frequent or occur at the end.
            LinkedList: Preferred when frequent insertions and deletions are required, especially at the beginning or middle of the list

          2.HashSet
          
          HashSet is a collection that implements the Set interface. It uses a hash table for storage, which means it does not guarantee any specific order of elements. 
          HashSet does not allow duplicate elements.

            Key Points:
            Implements the Set interface.
            Does not allow duplicate elements.
            Provides constant-time performance for basic operations like add, remove, and contains.

            
            

     11. Created custom LinkedList in Java
     12. Doubly Linked List
     13. File handling in Java
     14. Stack in Java
     15. Threads in Java
          Java Threading
          Java threading allows you to execute multiple threads (small units of a process) simultaneously, enabling multitasking and efficient use of resources.

            Creating Threads
            There are two main ways to create a thread in Java:

                   Extending Thread Class
                   Implementing Runnable Interface



                   
     16. Essentials for react
     17. Selenium Basics
     18. HTMLUnit
     
     

# Basics of Spring-boot

     1. Displaying a string
     2. Passing data through the path variable
     3. Finding the sum of numbers received from the path variable and returning it
     4. getting JSON data and displaying it using a GET request
     5. Carrying out operations on data in JSON format
     6. Finding the number of occurrences of a particular word in a sentence both are passed as JSON data and returning the count
     7. Accepting an Array of JSON data and displaying it
     8. Learned how the data flow works inside Springboot
     9. Learned the need for 4 layers in Springboot
     10. Learned to connect MySQL database with spring-boot application

# Projects Built

     1. Employee Management System 
                > Performed CREATE READ, UPDATE, AND DELETE operations using Springboot layer structure
                > Used Mysql database for storing and maintaining data 
                > Used functions from the repository in the service layer to handle Image files 
                > Used Axios Library to make HTTP request
                > Used POSTMAN to check the working of Endpoints (both path variable and request body)
                > Used Bootstrap for styling 
                > Used downloadjs library to give download options to the webpage

     2. Blog Posting Website    
                > Tech stacks used: Spirngboot, React 
                > Performed CREATE and READ operations using Springboot layer structure
                > Used Mysql database for storing and maintaining data 
                > Used POSTMAN to check the working of Endpoints (both path variable and request body)
                > Used Axios Library to make HTTP request
                > Used external Swiper libraries to implement swiping Operations
                > Used Forms to get data from the users
                > Used material UI for styling
                
     3. Movie Searching app
                > Tech stacks used: React 
                > Used Ombd API to fetch JSON data
                > Used react hooks like useState and useEffect
                > Deployed using Netlify via Github continuous development 

     4. 3d portfolio
          > Learned Three js
          > Learned tailwind css

     5 . Web Scraping project (PriceWise)   
          > Learned Nodejs
          > Used bright data
          
        
      

# Certifications

  1.Java course -Mastering the Fundamentals
  

![a4224fa72a89942720d5790e55bb228c083df0d68ce12af26adccc354db98b44](https://github.com/RAHULRNAIR2000/Java-Learnings/assets/83546515/b9402a3c-7a77-4fee-a344-1deccc3ef61b)



 2. Basics of Java -Coding Ninja

    ![certi_image5998634fec3814082d5bad6fcf4018a79de018](https://github.com/RAHULRNAIR2000/Java-Learnings/assets/83546515/e54a9ffb-4443-4d2c-a784-2a2bd79ab3d5)


 


 [certificate-599863-d69d41efe6c1cc47636d72e8b82c29f3.pdf](https://github.com/RAHULRNAIR2000/Java-Learnings/files/15298853/certificate-599863-d69d41efe6c1cc47636d72e8b82c29f3.pdf)

 3.Java-HackerRank


[java_basic certificate.pdf](https://github.com/user-attachments/files/16830253/java_basic.certificate.pdf)

![image](https://github.com/user-attachments/assets/a17f1522-381b-4d25-a44b-34197d18a45d)


