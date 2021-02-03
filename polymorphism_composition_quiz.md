# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Many shapes/forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Polymorphism in OO design is the principle that different classes should be able to work within the same interface

This is achieved through allowing classes to take on multiple types. Either through inheritance, interfaces or typecasting.
    
    public class Hippo extends Animal(
    
    )

^This means the class Hippo is both of type Hippo and type Animal.

3. What can we use to implement polymorphism in Java?

Parent classes or interfaces.

4. How many 'forms' can an object take when using polymorphism?

As many as you so design. However, a class can only 'extend' once (from a parent class), where as
it can 'implement' (from an interface) as many as desired.

5. Give an example of when you could use polymorphism.

When it is necessary to use a method with accepts an argument as a type that you don't currently have.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

It refers to the idea that a class can be build of multiple other classes as properties.

7. When would you use composition? Provide a simple example in Java.

To group componets under a common class ie, Books in a library.


    public class Library(
    
        private ArrayList<Book> books;
        
        public Library(ArrayList<Book> books){
            this.books = new ArrayList<>();
    )


8. What is/are the advantage(s) of using composition?

It allows you to be specific about the componets that are being included.

9. When an object is destroyed, what happens to all the objects it is composed of?
Also destroyed.