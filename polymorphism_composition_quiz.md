# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
Polymorphism refers to an object that can be made into different class types.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
In object oriented design, polymorphism allows child elements to have unique behaviours but still share some core functionality. For example in java you might furniture class. Both child classes a table class and a toilet class - can be placed in a room, have a name, and a price. But only the toilet class has a flushing method and a water capacity.

3. What can we use to implement polymorphism in Java?
To implement polymorphism we use abstract classes. These dictate what subclasses contain, and subclasses can be constructed easily by "extending" these superclasses, and using "super()", taking in supplemental parameters.

4. How many 'forms' can an object take when using polymorphism?
A class can only take on one abstract class by extending it. it can however implement multiple interfaces which allow other forms of polymorphism.

5. Give an example of when you could use polymorphism.
Maybe I am making a football team and I want a player superclass. They can kick ball, head ball and tackle. However, when I make a different class for each position - a defender, midfielder, forward and goalkeeper, I can make subclasses for each that have different functionality e.g. the goalkeeper can hold the ball and throw the ball, whereas only defenders can perform an offside trap.

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
In OO programming, the idea of composition refers to an object being composed of other objects; having them as opposed to being them;

7. When would you use composition? Provide a simple example in Java.
We use composition when we want to take in from different sources. Say we have produced an enemy class in the game; They all have a health value and a strength value with an attack method. BUT when we create our orc class and our warlock class, orcs would use spears and warlocks would use spells. it makes more sense for an Orc to HAVE a Spear, so that in its own attack method, it can use the Spear's throwSpear() function to attack enemies that are fair away, whereas the Warlock's attack method could HAVE a fog object of a spell class, which can be cast when it attacks.

8. What is/are the advantage(s) of using composition?
It is worth thinking of composition as being more flexible than the inheritance alternative, while the elements it has are likely to be far smaller and easier to change if we need, as opposed to the abstract superclass.

9. When an object is destroyed, what happens to all the objects it is composed of?
They are also destroyed. 
