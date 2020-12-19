# Dart Programming - Classes

<p>Dart is an object-oriented language. It supports object-oriented programming features like classes, interfaces, etc. A class in terms of OOP is a blueprint for creating objects. A class encapsulates data for the object. Dart gives built-in support for this concept called class.</p>

#### Declaring a Class

<p> Use the class keyword to declare a class in Dart. A class definition starts with the keyword class followed by the class name; and the class body enclosed by a pair of curly braces. The syntax for the same is given below</p>

>Syntax

```
class class_name {  
   <fields> 
   <getters/setters> 
   <constructors> 
   <functions> 
}
```

<p>The class keyword is followed by the class name. The rules for identifiers must be considered while naming a class.</p>

<p>A class definition can include the following </p>

<ul>
    <li>Fields − A field is any variable declared in a class. Fields represent data pertaining to objects.</li>
    <li>Setters and Getters − Allows the program to initialize and retrieve the values of the fields of a class. A default getter/ setter is associated with every class. However, the default ones can be overridden by explicitly defining a setter/ getter.</li>
    <li>Constructors − responsible for allocating memory for the objects of the class.</li>
    <li>Functions − Functions represent actions an object can take. They are also at times referred to as methods.</li>
</ul>

------
##### These components put together are termed as the data members of the class.

------

## Creating Instance of the class

<p>To create an instance of the class, use the new keyword followed by the class name. The syntax for the same is given below</p>

>Syntax

```
var object_name = new class_name([ arguments ])
```
<ul>
    <li>The new keyword is responsible for instantiation.</li>
    <li>The right-hand side of the expression invokes the constructor. The constructor should be passed values if it is parameterized.</li>
</ul>

------
## Accessing Attributes and Functions

<p>A class’s attributes and functions can be accessed through the object. Use the ‘.’ dot notation (called as the period) to access the data members of a class.</p>

```
//accessing an attribute 
obj.field_name  

//accessing a function 
obj.function_name()
```
-----

## Dart Constructors

<p>A constructor is a special function of the class that is responsible for initializing the variables of the class. Dart defines a constructor with the same name as that of the class. A constructor is a function and hence can be parameterized. However, unlike a function, constructors cannot have a return type. If you don’t declare a constructor, a default no-argument constructor is provided for you.</p>

>Syntax

```
Class_name(parameter_list) { 
   //constructor body 
}
```

## Named Constructors

<p>Dart provides named constructors to enable a class define multiple constructors. The syntax of named constructors is as given below</p>

> Syntax : Defining the constructor

```
Class_name.constructor_name(param_list)
```

------

## Dart Class ─ Getters and Setters

<p> Getters and Setters, also called as accessors and mutators, allow the program to initialize and retrieve the values of class fields respectively. Getters or accessors are defined using the get keyword. Setters or mutators are defined using the set keyword.

A default getter/setter is associated with every class. However, the default ones can be overridden by explicitly defining a setter/ getter. A getter has no parameters and returns a value, and the setter has one parameter and does not return a value.</p>

> Syntax: Defining a getter

```
Return_type  get identifier 
{ 
}
```

> Syntax: Defining a setter
```
set identifier 
{ 
}
```
## Class Inheritance

<p>Dart supports the concept of Inheritance which is the ability of a program to create new classes from an existing class. The class that is extended to create newer classes is called the parent class/super class. The newly created classes are called the child/sub classes.

A class inherits from another class using the ‘extends’ keyword. Child classes inherit all properties and methods except constructors from the parent class.</p>

> Syntax

```
class child_class_name extends parent_class_name 
```

### Types of Inheritance

<p>Inheritance can be of the following three types</p>

<ul>
    <li>Single − Every class can at the most extend from one parent class.</li>
    <li>Multiple − A class can inherit from multiple classes. Dart doesn’t support multiple inheritance.</li>
    <li>Multi-level − A class can inherit from another child class.</li>
</ul>