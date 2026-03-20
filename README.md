1. Introduction to Object-Oriented Programming (OOP)
Object-Oriented Programming is a programming paradigm based on the concept of "objects", which can contain data and code. The two main characteristics of OOP are
Classes and Objects.
3. Classes vs. Objects
Class:*A class is like a blueprint or a template. It defines the structure and behaviors that objects created from the class will have. It does not hold data itself; it defines *how* data should be stored.
Object: An object is an instance of a class. When you create a class, no memory is allocated. When you create an object (instantiate the class), memory is allocated.
Analogy: The Class is the architectural drawing of a house. The Object is the actual house built from that drawing.

4. Constructors (`__init__`)
Definition:A constructor is a special method that is automatically called when an object is created.
Purpose: It is used to initialize the object's state (assign values to object properties).
Syntax in Python:The constructor method is named `__init__`.
The `self` parameter:The first parameter of any method in a class must be `self`. It refers to the current instance of the class.

5. Destructors (`__del__`)
Definition: A destructor is a special method that is called when an object is about to be destroyed.
Purpose: It is used to perform cleanup activities before the object is removed from memory (e.g., closing database connections or files).
Syntax in Python:** The destructor method is named `__del__`.  matic Garbage Collector. You do not always need to write a destructor, and it is not guaranteed to run immediately when you delete an object, but it is useful for understanding object lifecycles.

5.TAKEAWAY
1.class = Blueprint.
2.Object= Instance of the blueprint.
3.Constructor = Runs at the start (Initialization).
4.Destructor= Runs at the end (Cleanup).
