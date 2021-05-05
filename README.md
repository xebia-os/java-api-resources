# Java learning path - from basic building blocks to API development
Curated collection of resources for learning API development in Java

This list assumes a familiarity with basic programming constructs. It is opinionated towards a practical subset of Java language.

## Legend

- :video_camera: Video talk
- :newspaper: Text article
- :book: Book
- :mortar_board: Online Course​

## Basics

### Courses

:mortar_board: Java Programming Masterclass for Software Developers - [Link](https://www.udemy.com/course/java-the-complete-java-developer-course/)

:mortar_board: Java In-Depth: Become a Complete Java Engineer! [Link](https://www.udemy.com/course/java-in-depth-become-a-complete-java-engineer/)

:mortar_board: Java Programming for Complete Beginners - Java 16 [Link](https://www.udemy.com/course/java-programming-tutorial-for-beginners/)

:mortar_board: The Complete Java Certification Course [Link](https://www.udemy.com/course/master-practical-java-development/)

### Books

:book: Head First Java - [Link](https://www.amazon.in/Head-First-Java-Brain-Friendly-Guide/dp/8173666024) Great if outdated, but still a good primer

### Practical concerns

- [ ] Setup your IDE - Eclipse or IntelliJ
- [ ] Install JDK 11 (preferred LTS version) - either from Oracle or OpenJDK or others

### Topics

##### Basic data types and their sizes

- [ ] int, float, long, double, char
- [ ] arrays

:newspaper: I Finally Understand Static vs. Dynamic Typing and You Will Too! - [Link](https://hackernoon.com/i-finally-understand-static-vs-dynamic-typing-and-you-will-too-ad0c2bd0acc7)

##### Flow control 

- [ ] if-else* conditionals
- [ ] *for* loops
- [ ] *while* loops (optional)
- [ ] methods
- [ ] exception handling

##### OOP building blocks

:video_camera:  Computer programming: What is object-oriented language? - [Link](https://www.youtube.com/watch?v=SS-9y0H3Si8)

- [ ] Classes
- [ ] constructors
- [ ] access modifiers
- [ ] Interfaces and Abstract class
- [ ] Inheritance
- [ ] Polymorphism

- [ ] Nested classes are useful but can be deferred until needed

:newspaper: How and why to override the equals method in Java - [Link](http://users.csc.calpoly.edu/~gfisher/classes/102/info/howToOverrideEquals.html)

- [ ] Wrapper classes and auto-boxing/unboxing

##### Java Collections classes (important)

:newspaper: Big O Cheatsheet - [Link](https://www.bigocheatsheet.com/)

- [ ] List, Set, Map
- [ ] Arrays utility class
- [ ] Collections utility class
- [ ] Iterators
- [ ] Comparable and Comparator

Oracle Java Tutorial Trail: Collections - [Link](https://docs.oracle.com/javase/tutorial/collections/index.html)

Outline of the Collections Framework - [Link](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/doc-files/coll-reference.html) Get comfortable reading javadoc for the major classes

Java Collections API Design FAQ - [Link](https://docs.oracle.com/javase/8/docs/technotes/guides/collections/designfaq.html)

#### Test driven development (essential)

:newspaper: Extreme programming - [Link](https://en.wikipedia.org/wiki/Extreme_programming)

:newspaper: 5 step method to make test-driven development and unit testing easy - [Link](https://codeutopia.net/blog/2016/10/10/5-step-method-to-make-test-driven-development-and-unit-testing-easy/)

:newspaper: Introduction to Test Driven Development (TDD) - [Link](http://agiledata.org/essays/tdd.html)

:newspaper: Unit Tests Are FIRST - [Link](https://pragprog.com/magazines/2012-01/unit-tests-are-first)

:video_camera: The Clean Code Talks -- Unit Testing - [Link](https://www.youtube.com/watch?v=wEhu57pih5w)

:video_camera: Test-driven development: Write better code in less time - [Link](https://www.youtube.com/watch?v=HhwElTL-mdI)

#### Programming problems

- Basic problems - [Here](./problems/01-basic.md)
- Basic design problems - [Link](./problems/02-OOP.md)

## Intermediate

### Books

:book: Effective Java - [Link](https://www.amazon.in/Effective-Java-Joshua-Bloch/dp/0134685997)

:book: Clean Code Summary - [Link](https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29)

:book: Head First Object-Oriented Analysis and Design: A Brain Friendly Guide to OOA&D - [Link](https://www.amazon.in/Head-First-Object-Oriented-Analysis-Design/dp/8184042213) (This book has some good small examples of OOP design problems)

### Topics

##### Generics

:newspaper: Java Generics FAQs by Angelika Langer - [Link](http://www.angelikalanger.com/GenericsFAQ/JavaGenericsFAQ.html) (This is densely theoretical and can be deferred for later)

:book: Effective Java: Chapter 5: Generics

:video_camera: Java Generics: Past, Present and Future by Richard Warburton/Raoul-Gabriel Urma - [Link](https://www.youtube.com/watch?v=LEAoMMEIUXk)

##### Lambdas and Streams

:newspaper: Java 8: The Missing Tutorial - [Link](https://github.com/shekhargulati/java8-the-missing-tutorial)

:video_camera: Get a Taste of Lambdas and Get Addicted to Streams - [Link](https://www.youtube.com/watch?v=1OpAgZvYXLQ)

:video_camera: The Power and Practicality of Immutability - [Link](https://www.youtube.com/watch?v=FQERMVABRrQ)

:video_camera: Refactoring to Java 8 - [Link](https://www.youtube.com/watch?v=NcetKbGayZY)

:video_camera: Twelve Ways to Make Code Suck Less - [Link](https://www.youtube.com/watch?v=nVZE53IYi4w)

:video_camera: Optional - The Mother of All Bikesheds - [Link](https://www.youtube.com/watch?v=Ej0sss6cq14)

### Practical Development concerns

:newspaper:  Git: The Missing Tutorial - [Link](https://github.com/shekhargulati/git-the-missing-tutorial/blob/master/README.md)

:newspaper: Naming a Package - [Link](https://docs.oracle.com/javase/tutorial/java/package/namingpkgs.html)

:newspaper: Package by feature, not layer - [Link](http://www.javapractices.com/topic/TopicAction.do;jsessionid=0BF4844350780B6F55476E1137FF4893?Id=205)

:newspaper: Package by type, -by layer, -by feature vs “Package by layered feature” - [Link](https://proandroiddev.com/package-by-type-by-layer-by-feature-vs-package-by-layered-feature-e59921a4dffa)

:video_camera:  42 IntelliJ IDEA Tips and Tricks - [Link](https://www.youtube.com/watch?v=eq3KiAH4IBI)

:video_camera: Be more productive with IntelliJ Idea - [Link](https://www.youtube.com/watch?v=CmPJzEqFS4s)

:video_camera: ​Code Refactoring - [Link](https://www.youtube.com/playlist?list=PLGLfVvz_LVvSuz6NuHAzpM52qKM6bPlCV)

### Software Design principles

:book: Effective Java Summary - [Link](https://github.com/HugoMatilla/Effective-JAVA-Summary)

:video_camera: Core Design Principles for Software Developers - [Link](https://www.youtube.com/watch?v=llGgO74uXMI)

:book: Effective Java: Chapter 10: Exceptions

:newspaper:Fluent Interface - [Link](https://martinfowler.com/bliki/FluentInterface.html)

:video_camera: SOLID Principles - [Link](https://www.youtube.com/playlist?list=PLdR9bD5hyZiiCr5pDs8tYmzHosz3tqIuD)

📹 Object-oriented Design of a Shopping Cart with TDD - [Link](https://www.youtube.com/watch?v=5UmsIoJI9Is)

#### Programming problems

- Functional programming - [Here](./problems/03-lambdas.md)


