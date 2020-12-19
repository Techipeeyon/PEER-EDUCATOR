# Week-3

## Introduction to Dart
<p>Dart is an open-source general-purpose programming language. It is originally developed by Google and later approved as a standard by ECMA. Dart is a new programming language meant for the server as well as the browser. Introduced by Google, the Dart SDK ships with its compiler – the Dart VM. The SDK also includes a utility -dart2js, a transpiler that generates JavaScript equivalent of a Dart Script.</p>

<p>Dart is an object-oriented language with C-style syntax which can optionally trans compile into JavaScript. It supports a varied range of programming aids like interfaces, classes, collections, generics, and optional typing.</p>

>Features of Dart:
------

|    FEATURE  |       DART                  |
| ------------| --------------------------- |
|Type system  | Optional, dynamic           |
|Classes      | Yes, single inheritance     |    
|Interfaces   | Yes, multiple interfaces    |  

------

## Dart Prgramming Syntax

<p>Syntax defines a set of rules for writing programs. Every language specification defines its own syntax. A Dart program is composed of,</p>

<ul>
    <li>Variables and Operators</li>
    <li>Classes</li>
    <li>Functions</li>
    <li>Expressions and Programming Constructs</li>
    <li>Decision Making and Looping Constructs</li>
    <li>Comments</li>
    <li>Libraries and Packages</li>
    <li>Typedefs</li>
    <li>Data structures represented as Collections / Generics</li>

 >Simple Hello World dart code

 ```
  main() { 
   print("Hello World!"); 
}
```
<p>   The main() function is a predefined method in Dart. This method acts as the entry point to the application. A Dart script needs the main() method for execution. print() is a predefined function that prints the specified string or value to the standard output i.e. the terminal.</p>


###	Command-Line Option & Description

```-c or --c```

Enables both assertions and type checks (checked mode).

```--version```

Displays VM version information.

```--packages```
<path>

Specifies the path to the package resolution configuration file.

```-p```

 <path>
Specifies where to find imported libraries. This option cannot be used with --packages.





```-h or --help```
	
Displays help.

------

<p>The following tables lists a few examples of valid and invalid identifiers</p>

|    Valid Identifiers  |       Invalid Identifiers                 |
| ------------| --------------------------- |
| firstName | Var           |
|first_name      |   first name   |    
| num1  |   first-name  |  
| $result| 1number |

------

## Comments in Dart

<p>
Comments are a way to improve the readability of a program. Comments can be used to include additional information about a program like author of the code, hints about a function/ construct etc. Comments are ignored by the compiler.</p>
<p>Dart supports the following types of comments </p>
<ol>
    <li> Single-line comments ( // ) : Any text between a "//" and the end of a line is treated as a comment </li>
    <li>Multi-line comments (/* */) − These comments may span multiple lines.</li>
    </ol>

```
// this is single line comment  
  
/* This is a   
   Multi-line comment  
*/
```

### Object-Oriented Programming in Dart
<p>Dart is an Object-Oriented language. Object Orientation is a software development paradigm that follows real-world modelling. Object Orientation considers a program as a collection of objects that communicate with each other via mechanism called methods</p>

<ul>
<li>Object − An object is a real-time representation of any entity. As per Grady Brooch, every object must have three features</li>
<li>State − described by the attributes of an object.</li>
<li>Behavior − describes how the object will act.</li>
<li>Identity − a unique value that distinguishes an object from a set of similar such objects.</li>
<li>Class − A class in terms of OOP is a blueprint for creating objects. A class encapsulates data for the object</li>
<li>Method − Methods facilitate communication between objects.</li>

------