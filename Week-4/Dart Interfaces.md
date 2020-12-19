# Dart Programming - Interfaces

<p>An interface defines the syntax that any entity must adhere to. Interfaces define a set of methods available on an object. Dart does not have a syntax for declaring interfaces. Class declarations are themselves interfaces in Dart.</p>
<p>Classes should use the implements keyword to be able to use an interface. It is mandatory for the implementing class to provide a concrete implementation of all the functions of the implemented interface. In other words, a class must redefine every function in the interface it wishes to implement.</p>

>Syntax: Implementing an Interface

```
class identifier implements interface_name
```
------

#### Implementing Multiple Interfaces

<p>A class can implement multiple interfaces. The interfaces are separated by a comma. The syntax for the same is given below</p>

>Syntax for implementing multiple interface

```
class identifier implements interface-1,interface_2,interface_4…….
```