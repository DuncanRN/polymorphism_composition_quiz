# Polymorphism
# What does the word 'polymorphism' mean?

A variable can be two (or more) different types. It will be one at a time, but can be cast into the others.


#  What does it mean when we apply polymorphism to OO design? Give a simple Java example.

A car variable can be of type Vehicle (the super class) and be cast into the sub class Car. For example if methods within the class Car are required.
This variable can be two different types, it is polymorphic.



# What can we use to implement polymorphism in Java?

if car is a Vehicle type, we can use (Car) car to cast it back into a Car type.



# How many 'forms' can an object take when using polymorphism?

I feel like you want me to say 2. But by my understanding the answer is many. I understand it to be limitless (theoretically...)

If we can cast a dog variable of Mammal type back down to Dog type.... 

then can't Mammal also be a sub class of Animal? 

And can't Animal be a subclass of LivingThing...? 

Might need to talk this one through!


# Give an example of when you could use polymorphism.

When needing to access the methods defined in the class Car, but our current car variable is of type Vehicle. We'd cast it back to car.



# Composition and Aggregation
# What do we mean by 'composition' in reference to object-oriented programming?

A class which contains a variable of type "another class".



# When would you use composition? Provide a simple example in Java.

The example from today was for a Car class each car has an engine of class Engine.
Another example would be... a CodeClan student class woud define a student as having a laptop of class Laptop.

# Give a difference between composition and aggregation?

Aggregation is when a class "has a" other class contained in it.

The objects are independent of one another.

Composition is when objects are tightly coupled on each other. They are dependent on each other.
If the parent is deleted then the child is deleted too.



# What is/are the advantage(s) of using composition/aggregation?

Is this question asking about composition/aggregation compared to inheritance? I wil answer it with that assumption- 

There are many times where it is truer to say x is made up of y / x has a y. Rather than x is a more specific type of y.




#  When using composition, when an object is destroyed, what happens to all the objects it is composed of?

They are destroyed.


# When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

They still exist.
