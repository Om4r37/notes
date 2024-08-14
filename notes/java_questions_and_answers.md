What is Java?
- it's an object oriented statically typed, compiled programming language that runs on it's own virtual machine.

What are the features of Java?
- Object Oriented, Platform Independent, Secure, Architecture Neutral, Portable, Multithreaded, Performant (with JIT)

What is JVM?
- an abstract machine that provides a runtime environment in which Java bytecode can be executed,
it has its own ISA, memory, stack, heap, etc,
runs on the host OS,
is a specification and can have different implementations (Oracle HotSpot, IBM J9),
can execute any language that compiles to java bytecode (like kotlin),
and has the following components:
    - Class Loader: loads class files into memory (bootstrap, extension, application).
    - Bytecode Verifier: verifies the bytecode.
    - stacks and program counters: for each thread.
    - heap: memory area for objects and arrays.
    - Method Area: stores Run-Time Constant Pool for each class.
    - Garbage Collector (GC): manages memory in the heap.
    - Execution Engine: interprets the bytecode and executes it.
    - JIT Compiler: compiles the bytecode to native machine code.
    - Java Native Interface (JNI): allows Java code to call native code.
    - Native Method Libraries and Stacks.

What is JRE?
- it's the environment that provides the class libraries and other resources that a specific Java program requires to run.

What is JDK?
- it provides the tools needed to develop Java applications (compiler, VM, etc).

What is the main difference between Java and other programming languages?
- other compiled languages were compiled to run on a specific platform, Java is compiled to run on a virtual machine.

What do you mean by platform independence in Java?
- Java is compiled to bytecode that can run on any platform that has a JVM.

What is the difference between JDK, JRE, and JVM?
- JDK includes tools like compiler, JVM and JRE. JRE includes JVM and runtime libraries. JVM loads and runs the bytecode.

What is the Java Virtual Machine (JVM) and how is it considered in the context of Java's platform independence?
- the same bytecode can run on any platform that has a JVM, the JVM can be implemented on any platform.

What is a class in Java?
- a class is a blueprint for objects.

What is an object in Java?
- an entity that has states and behavior and is an instance of a class.

What is the difference between an object and a class?
- a class is a blueprint, an object is an instance of a class.

What are the OOP principles in Java?
- Inheritance, Encapsulation, Polymorphism, Abstraction.

What is inheritance in Java?
- a class can inherit fields and methods from another class.

What is polymorphism in Java?
- a method can have different implementations.

What is abstraction in Java?
- hiding the implementation details.

What is encapsulation in Java?
- restricting access to some components of an object and exposing only what's necessary.

What is the difference between abstraction and encapsulation in Java?
- abstraction is about hiding the implementation details, encapsulation is about restricting access to some components of an object.

What is an interface in Java?
- a class where all methods are abstract and it defines the methods that a class must implement.

What is the difference between a class and an interface?
- a class can have fields and methods, an interface can only have abstract methods.

What is an abstract class in Java?
- a class that cannot be instantiated and can have abstract methods.

Can we instantiate an abstract class?
- no.

What is the difference between an abstract class and an interface?
- an abstract class can have fields and methods, an interface can only have abstract methods.

What is a constructor in Java?
- a special method that is called when an object is created.

What are the types of constructors in Java?
- default, no-arg, parameterized.

Can a constructor be private?
- yes.

What is method overloading in Java?
- having multiple methods with the same name but different parameters.

What is method overriding in Java?
- having a method in a subclass with the same signature as a method in the superclass but with a different implementation.

What is the difference between method overloading and method overriding?
- method overloading is having multiple methods with the same name but different parameters, method overriding is having a method in a subclass with the same signature as a method in the superclass but with a different implementation.

What is the use of the 'super' keyword in Java?
- it's used to refer to the superclass.

What is the use of the 'this' keyword in Java?
- it's used to refer to the current object.

What is inheritance and what are its types?
- inheriting fields and methods from another class, types are single, multilevel, hierarchical.

Can we override the static method in Java?
- no.

What is a static variable in Java?
- a variable that belongs to the class and not to the object.

What is a static method in Java?
- a method that belongs to the class and not to the object.

What is a static block in Java?
- a block of code that is executed when the class is loaded.

Can we make a constructor static in Java?
- no.

What is the final keyword in Java?
- it's used to restrict changing the value of a variable, extending a class, overriding a method.

What is the difference between the final, finally, and finalize keywords?
- final is used to restrict changing the value of a variable, extending a class, overriding a method, finally is used in exception handling, finalize is a method that is called by the garbage collector before an object is destroyed.

What is an exception in Java?
- an event that disrupts the normal flow of the program.

What is the difference between checked and unchecked exceptions?
- checked exceptions are checked at compile time, unchecked exceptions are not.

What is the use of the 'throws' keyword in Java?
- it's used to declare that a method may throw an exception.

What is the difference between 'throw' and 'throws'?
- throw is used to throw an exception, throws is used to declare that a method may throw an exception.

What is exception handling in Java?
- handling exceptions that may occur during the execution of a program.

What are the five keywords used in exception handling?
- try, catch, finally, throw, throws.

What is a try-catch block in Java?
- a block of code that is executed and if an exception occurs it's caught by the catch block.

What is the use of the finally block in exception handling?
- it's used to execute code that should always run, like closing a file.

Can we have multiple catch blocks for a single try block?
- yes.

What is the difference between 'String', 'StringBuilder', and 'StringBuffer'?
- String is immutable, StringBuilder is mutable, StringBuffer is a thread-safe (synchronized) StringBuilder but it has a performance penalty.

What is the use of the 'equals()' method in Java?
- it's used to compare two objects.


What is the use of the 'hashCode()' method in Java?
- it's used to get the hash code of an object.

What is the 'toString()' method in Java?
- it's used to get a string representation of an object.

What is a package in Java?
- a namespace that contains related classes and interfaces.

What is the difference between import and static import in Java?
- static import allows you to access static members of a class without using the class name.

What is the Java Collection Framework?
- a set of classes and interfaces that implement commonly reusable collection data structures.

What are the main interfaces of the Java Collection Framework?
- Collection, List, Set, SortedSet, Map, Map.Entry, SortedMap, Enumeration.

What is the List interface in Java?
- an ordered collection that allows duplicate elements.

What is the Set interface in Java?
- a collection that does not allow duplicate elements.

What is the Map interface in Java?
- a collection that maps keys to values.

What is the difference between List, Set, and Map?
- unlike List, Set does not allow duplicate elements, Map maps keys to values.

What is the difference between ArrayList and LinkedList in Java?
- ArrayList is an array, LinkedList is a doubly linked list.

What is the difference between HashSet and TreeSet in Java?
- HashSet is unordered, TreeSet is ordered.

What is the difference between HashMap and TreeMap in Java?
- HashMap is unordered, TreeMap is ordered.

What is an Iterator in Java?
- an interface that allows you to iterate over a collection.

What is the difference between Iterator and ListIterator?
- ListIterator is an iterator for lists that allows you to iterate in both directions.

What is the use of the 'forEach' method in Java?
- it's used to iterate over a collection.

What is the difference between Comparable and Comparator interfaces?
- Comparable is used to compare objects, Comparator is used to compare objects in a custom way.

What is a lambda expression in Java?
- a way to represent a function as an object.

What is a functional interface in Java?
- an interface that has only one abstract method.

What is the Stream API in Java?
- a new API in Java 8 that allows you to process collections of objects in a functional way.

What is the use of the 'filter' method in Stream API?
- it's used to filter (remove) elements of a collection.

What is the use of the 'map' method in Stream API?
- it's used to transform (apply a function on) elements of a collection.

What is the difference between 'map' and 'flatMap' in Stream API?
- map transforms each element of a collection, flatMap transforms each element of a collection into a stream of elements.

What is a default method in an interface?
- a method that has a default implementation.

What is the use of the 'try-with-resources' statement in Java?
- it's used to automatically close resources.

What is synchronization in Java?
- it's used to prevent multiple threads from accessing the same resource at the same time.

What is a deadlock in Java?
- a situation where two or more threads are waiting for each other to release a resource.

What is a thread in Java?
- a lightweight process that runs in the context of a program.

What is the difference between a process and a thread?
- a process is an instance of a program, a thread is a lightweight process that runs in the context of a program.

What is the use of the 'synchronized' keyword in Java?
- it's used to synchronize access to a block of code or a method.

What is the difference between 'wait()' and 'sleep()' methods?
- sleep stops the thread for a specified amount of time, wait stops the thread until another thread notifies, and it's used in synchronization.

What is a daemon thread in Java?
- a thread that runs in the background and does not prevent the JVM from exiting.

What is the 'ThreadLocal' class in Java?
- a class that provides thread-local variables.

What is the difference between 'Runnable' and 'Callable' interfaces?
- Runnable does not return a result, Callable returns a result.

What is the Java Memory Model (JMM)?
- a specification that defines how threads interact through memory.

What is garbage collection in Java?
- the process of reclaiming memory that is no longer used by the program.

What is the difference between 'finalize()' and 'dispose()' methods?
- finalize is a method that is called by the garbage collector before an object is destroyed, dispose is a method that is used to release resources.

What are the different types of garbage collectors in Java?
- Serial, Parallel, CMS, G1, Z, Shenandoah, Epsilon.

What are Java annotations?
- metadata that provides data about a program (like @Override).

What is the use of the '@Override' annotation in Java?
- it's used to indicate that a method overrides a method in the superclass.

What is reflection in Java?
- the ability of a program to examine and modify its own structure.

What is the use of the 'Class' class in Java?
- it represents a class at runtime.

What is the Java Native Interface (JNI)?
- a framework that allows Java code to call native code.

What is the purpose of the 'javap' tool in Java?
- it's used to disassemble a class file.

What is the difference between JIT and AOT compilation?
- JIT compiles the bytecode to native machine code at runtime, AOT compiles the bytecode to native machine code ahead of time.

What are the new features in Java 8?
- Lambda expressions, Stream API, Default methods, Functional interfaces, Optional class, Date and Time API.

What is the difference between 'java' and 'javac' commands?
- java is used to run the bytecode, javac is used to compile the source code.

What is a classloader in Java?
- it's a subsystem of the JVM that is used to load classes into memory.

What are the different types of classloaders in Java?
- Bootstrap, Extension, Application.


What is a switch expression in Java?
- it's a new feature in Java 12 that allows you to use a switch statement as an expression that returns a value.

What is a local variable type inference in Java?
- LVTI lets the compiler figure out the type of the variable.

What is the 'var' keyword in Java?
- you can use the var keyword instead of the full type name (similar to auto in c++);

What is the difference between a public, protected, and private access modifier?
- public: everyone can access.
- private: only the current class can access.
- protected: current class and subclasses can access.

What is the default access modifier in Java?
- package. (only current package can access).

What is a module descriptor in Java?
- a collection of classes that states all the required information to use that module.