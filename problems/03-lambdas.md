# Intermediate problems

1. Write a lambda function that takes a String and Integer and return an Integer
2. Write a functional interface `Sender`  that takes a String and writes the message to console. Also, write corresponding lambda function.
3. Write a lambda function that takes a String and writes it to a file.
4. `ThreadLocal` lambda expressions. Java has a class called `ThreadLocal` that acts as a container for a value that’s local to your current thread. In Java 8 there is a new factory method for `ThreadLocal` that takes a lambda expression, letting you create a new ThreadLocal without the syntactic burden of subclassing.
   * Find the method in Javadoc or using your IDE. 

   * The Java DateFormatter class isn’t thread-safe. Use the constructor to create a thread-safe DateFormatter instance that prints dates like this: `01-Jan-1970`.
5. Write a that is composed of two functions - 
   1. A function that takes any object and return its String representation 
   2. A function that takes a String and return an integer. The composed function will take an object and return an integer