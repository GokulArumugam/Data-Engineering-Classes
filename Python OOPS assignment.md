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

### Q18. Describe three applications for exception processing.

Try and except statements are used to catch and handle exceptions in Python. Statements that can raise exceptions are kept inside the try clause and the statements that handle the exception are written inside except clause.

Example: Let us try to access the array element whose index is out of bound and handle the corresponding exception.
  
### Q19. What happens if you don't do something extra to treat an exception?

if you don't handle exceptions, When an exception occurred, if you don't handle it, the program terminates abruptly and the code past the line that caused the exception will not get executed.

### Q20. What are your options for recovering from an exception in your script?

You can also provide a generic except clause, which handles any exception. After the except clause(s), you can include an else-clause. The code in the else-block executes if the code in the try: block does not raise an exception. The else-block is a good place for code that does not need the try: block's protection.

### Q21. Describe two methods for triggering exceptions in your script.

To avoid such a scenario, there are two methods to handle Python exceptions:
* Try – This method catches the exceptions raised by the program.
* Raise – Triggers an exception manually using custom exceptions.

### Q22. Identify two methods for specifying actions to be executed at termination time, regardless of whether or not an exception exists.

The finally Clause

This clause is meant to define clean-up actions that must be performed regardless of whether an exception was raised or not. A finally clause must always be executed before leaving the try/except statement, whether an exception has occurred or not.

### Q23. What is the purpose of the try statement?

The try statement allows you to define a block of code to be tested for errors while it is being executed. The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

### Q24. What are the two most popular try statement variations?

The Different Try/Except Variations. So far we've used a try / except and even a try / except / except , but this is only two-thirds of the story. There are two other optional segments to a try block: else and finally . Both of these optional blocks will come after the try and the except .

### Q25. What is the purpose of the raise statement?

The RAISE statement stops normal execution of a PL/SQL block or subprogram and transfers control to an exception handler. RAISE statements can raise predefined exceptions, such as ZERO_DIVIDE or NO_DATA_FOUND , or user-defined exceptions whose names you decide.

### Q26. What does the assert statement do, and what other statement is it like?

The assert keyword is used when debugging code. The assert keyword lets you test if a condition in your code returns True, if not, the program will raise an AssertionError. You can write a message to be written if the code returns False.

### Q27. What is the purpose of the with/as argument, and what other statement is it like?

The with statement is a replacement for commonly used try/finally error-handling statements. A common example of using the with statement is opening a file. 

### Q28. What are *args, **kwargs?

*args specifies the number of non-keyworded arguments that can be passed and the operations that can be performed on the function in Python whereas **kwargs is a variable number of keyworded arguments that can be passed to a function that can perform dictionary operations.

### Q29. How can I pass optional or keyword parameters from one function to another?

Users can either pass their values or can pretend the function to use theirs default values which are specified. In this way, the user can call the function by either passing those optional parameters or just passing the required parameters. Without using keyword arguments. By using keyword arguments.

### Q30. What are Lambda Functions?

A lambda function is a small anonymous function.
A lambda function can take any number of arguments, but can only have one expression.

### Q31. Explain Inheritance in Python with an example?

Inheritance relationship defines the classes that inherit from other classes as derived, subclass, or sub-type classes. Base class remains to be the source from which a subclass inherits. For example, you have a Base class of “Animal,” and a “Lion” is a Derived class. The inheritance will be Lion is an Animal.

### Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked?

If both classes A and B have a func() method, and class C inherits from both A and B, then the func() method from class A is invoked when called from an object of class C.

### Q33. Which methods/functions do we use to determine the type of instance and inheritance?

Two built-in functions isinstance() and issubclass() are used to check inheritances. The function isinstance() returns True if the object is an instance of the class or other classes derived from it.

### Q34.Explain the use of the 'nonlocal' keyword in Python.

The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function. Use the keyword nonlocal to declare that the variable is not local.

### Q35. What is the global keyword?

In Python, global keyword allows you to modify the variable outside of the current scope. It is used to create a global variable and make changes to the variable in a local context.
