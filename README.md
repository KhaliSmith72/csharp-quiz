# C# QUIZ

- What is an interface?
An Interface is a contract
- What is polymorphism?  Describe an example?
Ill describe it in an example. You have a method that gets the area of parallelograms. But each one has a different way of finding the area. So your method has many implementations.
- What is the difference between a class and an object?
A class is the blueprint for an object, where as objects are instantiated in the class.
- What are the four pillars of OOP?
polymorphism, encapsulation, abstraction, inheritance
- What is an abstract class?
an abstract class has methods, but none of them can be implemented.
- What is the difference between an abstract class and an interface?
interfaces have methods that can be implemented were as abstract classes do not.
- TRUE or FALSE: an abstract class can be instantiated?
False
- TRUE or FALSE: an abstract class can have a constructor?
True
- Is a string a value type or a reference type?  
value type
- What is the package management system used in Visual Studio?
NuGet
- After the following method executes and is completed what will be the value of the Name property of the Employee parameter object?

````

public static void UpdateEmployee(Employee employee)
{
    employee.Name = "Harry Potter";
}

````
Harry Potter....

- Will the Employee parameter object in the following method become null after the method executes and is completed?  Why or why not?

````

public static void NullEmployee(Employee employee)
{
    employee = null;
}

````
You declared it as null, but I believe I recall you saying that objects without set values are null by default.

- Create a class named Employee with the properties to hold the following info:
  - first name
  - last name
  - hire date
  - email

- Create an Employee object from the class defined above.  Give this object the following information:
  - first name: Harry
  - last name: Potter
  - hire date: 1/1/2015
  - email: harry.potter@gmail.com

- Take the Employee class created from the previous example and override the ToString() method to return a string representation of the properties.  Use string interpolation.

- Create a static method on the Employee class named CloneEmployee that takes an Employee object as a parameter and returns a deep copy.

- Create a method on the Employee class that returns the number of days an employee has been employed.

- Create a list of Employee objects.  Add three Employee objects to the list.  Iterate over the list of objects and call each object's ToString() method on each iteration.
