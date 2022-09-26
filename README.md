# Prerequisites
- Java SE: 
Oracle [releases](https://www.oracle.com/java/technologies/java-se-support-roadmap.html) new Java SE versions every 6 months, on March and September, but some of these are long-term supported versions.
Enterprises typically use these LTS versions, hopefully the latest available. As of this writing, the latest Java LTS version is Java 17,
which you have to download from [Oracle download's site](https://www.oracle.com/java/technologies/downloads/) and install.

- Integrated Development Environment (IDE):
This is a tool you'll use in your daily work as a developer. I've tried Eclipse, NetBeans, and IntelliJ Idea,
and I recommend you to [download IntelliJ Idea](https://www.jetbrains.com/idea/download/#section=linux), the community edition doesn't require paying a license to use it.


# Java Virtual Machine (JVM), Java Runtime Environment (JRE), Java Development Kit (JDK), Java Standard Edition (SE) and JakartaEE
Java is a compiled language that, unlike C/C++ programs (which have to be compiled for a specific
CPU like x86_64 or arm64), runs in the Java Virtual Machine (JVM). Time ago, Java could be downloaded from Oracle as either the
Java Runtime Environment (JRE), which only comprised the JVM necessary to run Java compiled programs, or as the Java Development Kit (JDK) which
not only contains the JVM, but also the Java compiler as well as other tools.

Finally, Java programming language is a rich ecosystem, and there have been several tools/frameworks built on top of it, to ease development 
and deployment of enterprise applications, for instance JakartaEE (previously named JavaEE and even J2EE) or Spring


# Introduction to Java
These videos introduce the Java language: https://testautomationu.applitools.com/java-programming-course/ and are a first approach to it.


# Oracle's certification topics
The [topics included in Oracle's Java programmer certification](https://education.oracle.com/cat%C3%A1logo-de-productos-ouexam-pexam_1z0-829/pexam_1Z0-829) 
exam are a good starting point for topics you should be really familiar with.

Handling date, time, text, numeric and boolean values

   - Use primitives and wrapper classes including Math API, parentheses, type promotion, and casting to evaluate arithmetic and boolean expressions
   - Manipulate text, including text blocks, using String and StringBuilder classes
   - Manipulate date, time, duration, period, instant and time-zone objects using Date-Time API

Controlling Program Flow

   - Create program flow control constructs including if/else, switch statements and expressions, loops, and break and continue statements

Utilizing Java Object-Oriented Approach
   - Declare and instantiate Java objects including nested class objects, and explain the object life-cycle including creation, reassigning references, and garbage collection
   - Create classes and records, and define and use instance and static fields and methods, constructors, and instance and static initializers
   - Implement overloading, including var-arg methods
   - Understand variable scopes, use local variable type inference, apply encapsulation, and make objects immutable
   - Implement inheritance, including abstract and sealed classes. Override methods, including that of Object class. Implement polymorphism and differentiate object type versus reference type. Perform type casting, identify object types using instanceof operator and pattern matching
   - Create and use interfaces, identify functional interfaces, and utilize private, static, and default interface methods
   - Create and use enumerations with fields, methods and constructors

Handling Exceptions

   - Handle exceptions using try/catch/finally, try-with-resources, and multi-catch blocks, including custom exceptions

Working with Arrays and Collections

   - Create Java arrays, List, Set, Map, and Deque collections, and add, remove, update, retrieve and sort their elements

Working with Streams and Lambda expressions

   - Use Java object and primitive Streams, including lambda expressions implementing functional interfaces, to supply, filter, map, consume, and sort data
   - Perform decomposition, concatenation and reduction, and grouping and partitioning on sequential and parallel streams

Packaging and deploying Java code and use the Java Platform Module System

   - Define modules and their dependencies, expose module content including for reflection. Define services, producers, and consumers
   - Compile Java code, produce modular and non-modular jars, runtime images, and implement migration using unnamed and automatic modules

Managing concurrent code execution

   - Create worker threads using Runnable and Callable, manage the thread lifecycle, including automations provided by different Executor services and concurrent API
   - Develop thread-safe code, using different locking mechanisms and concurrent API
   - Process Java collections concurrently including the use of parallel streams

Using Java I/O API

   - Read and write console and file data using I/O Streams
   - Serialize and de-serialize Java objects
   - Create, traverse, read, and write Path objects and their properties using java.nio.file API

Accessing databases using JDBC

   - Create connections, create and execute basic, prepared and callable statements, process query results and control transactions using JDBC API

Implementing Localization

   - Implement localization using locales, resource bundles, parse and format messages, dates, times, and numbers including currency and percentage values

Candidates are also expected to:

    - Understand the basics of Java Logging API.
    - Use Annotations such as Override, Functionalnterface, Deprecated, SuppressWarnings, and SafeVarargs.
    - Use generics, including wildcards.


# Oracle has tutorials for Java new joiners:
https://docs.oracle.com/javase/tutorial/tutorialLearningPaths.html#newtojava





