# Employee_Payroll-_System

The Java Employee Payroll System project utilizes several key Object-Oriented Programming (OOPS) concepts, like:

Abstraction: The project defines an abstract class Employee that encapsulates common properties and methods for both full-time and part-time employees. This allows for hiding complex implementation details while exposing only necessary functionalities.

Encapsulation: The use of private variables (like name and id) in the Employee class ensures that the data is protected from direct access. Accessors (getters) and mutators (setters) are used to interact with these variables, maintaining control over how they are accessed and modified.

Inheritance: The project demonstrates inheritance by creating subclasses FullTimeEmployee and PartTimeEmployee that extend the Employee class. This allows these subclasses to inherit properties and methods from the parent class while also adding their specific attributes and behaviors.

Polymorphism: The project likely employs polymorphism through method overriding, where subclasses can provide specific implementations of methods defined in the abstract parent class. This allows for dynamic method resolution at runtime, enabling flexibility in how employee types are handled.

This : is used to refer to the current instance of the class.

Super : To inherit properties of super class Employee to sub-classes Fulltime and Parttime.

These concepts work together to create a structured and efficient payroll management system, facilitating better organization and management of employee data.
