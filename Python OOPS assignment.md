### Q1. What is the purpose of Python's OOP?

In Python, object-oriented Programming (OOPs) is a programming paradigm that uses objects and classes in programming. It aims to implement real-world entities like inheritance, polymorphisms, encapsulation, etc. in the programming.

### Q2. Where does an inheritance search look for an attribute?

An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses, progressing from left to right (by default). The search stops at the first place the attribute is found.

### Q3. How do you distinguish between a class object and an instance object?

A class is a template for creating objects in a program, whereas the object is an instance of a class. A class is a logical entity, while an object is a physical entity. A class does not allocate memory space; on the other hand, an object allocates memory space.

### Q4. What makes the first argument in a class’s method function special?

meth(args) becomes Class.
This is the reason the first parameter of a function in class must be the object itself. Writing this parameter as self is merely a convention. It is not a keyword and has no special meaning in Python.

### Q5. What is the purpose of the init method?

The __init__ function is called every time an object is created from a class. The __init__ method lets the class initialize the object's attributes and serves no other purpose.

### Q6. What is the process for creating a class instance?

Instantiating a Class
The new operator requires a single, postfix argument: a call to a constructor. The name of the constructor provides the name of the class to instantiate. The new operator returns a reference to the object it created.

### Q7. What is the process for creating a class?

Declaration − A variable declaration with a variable name with an object type. Instantiation − The 'new' keyword is used to create the object. Initialization − The 'new' keyword is followed by a call to a constructor. This call initializes the new object.

### Q8. How would you define the superclasses of a class?

A superclass is the class from which many subclasses can be created. The subclasses inherit the characteristics of a superclass. The superclass is also known as the parent class or base class. In the above example, Vehicle is the Superclass and its subclasses are Car, Truck and Motorcycle.

### Q9. What is the relationship between classes and modules?

Modules are collections of methods and constants. They cannot generate instances. Classes may generate instances (objects), and have per-instance state (instance variables).

### Q10. How do you make instances and classes?

To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

### Q11. Where and how should be class attributes created?

* A class attribute is shared by all instances of the class. To define a class attribute, you place it outside of the __init__() method.
* Use class_name.class_attribute or object_name.class_attribute to access the value of the class_attribute.
* Use class attributes for storing class contants, track data across all instances, and setting default values for all instances of the class.

### Q12. Where and how are instance attributes created?

Instance attributes are defined in the constructor. Defined directly inside a class. Defined inside a constructor using the self parameter.

### Q13. What does the term "self" in a Python class mean?

The self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class.

### Q14. How does a Python class handle operator overloading?

The operator overloading in Python means provide extended meaning beyond their predefined operational meaning. Such as, we use the "+" operator for adding two integers as well as joining two strings or merging two lists. We can achieve this as the "+" operator is overloaded by the "int" class and "str" class.

### Q15. When do you consider allowing operator overloading of your classes?

The operator overloading in Python means provide extended meaning beyond their predefined operational meaning. Such as, we use the "+" operator for adding two integers as well as joining two strings or merging two lists. We can achieve this as the "+" operator is overloaded by the "int" class and "str" class.

### Q16. What is the most popular form of operator overloading?

A very popular and convenient example is the Addition (+) operator. Just think how the '+' operator operates on two numbers and the same operator operates on two strings. It performs “Addition” on numbers whereas it performs “Concatenation” on strings.

### Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?

Both inheritance and polymorphism are key ingredients for designing robust, flexible, and easy-to-maintain software. These concepts are best explained via examples. Let's start with creating a simple class.
