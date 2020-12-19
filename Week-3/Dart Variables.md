# Dart Programming - Variables

<p>A variable is “a named space in the memory” that stores values. In other words, it acts a container for values in a program. Variable names are called identifiers. Following are the naming rules for an identifie</p>

<ul>
    <li>Identifiers cannot be keywords.</li>
    <li>Identifiers can contain alphabets and numbers.</li>
    <li>Identifiers cannot contain spaces and special characters, except the underscore (_) and the dollar ($) sign.</li>
    <li>Variable names cannot begin with a number.</li>
</ul>

------

### Type Syntax

<p>A variable must be declared before it is used. Dart uses the var keyword to achieve the same. The syntax for declaring a variable is as given below</p>

```
var name = 'Smith';
```

<p>
All variables in dart store a reference to the value rather than containing the value. The variable called name contains a reference to a String object with a value of “Smith”.</p>

<p>Dart supports type-checking by prefixing the variable name with the data type. Type-checking ensures that a variable holds only data specific to a data type. The syntax for the same is given below</p>

```
String name = 'Smith'; 
int num = 10;
```

#### The dynamic keyword

<p>Variables declared without a static type are implicitly declared as dynamic. Variables can be also declared using the dynamic keyword in place of the var keyword.</p>

```
void main() { 
   dynamic x = "tom"; 
   print(x);  
}
```
##### Output
```
tom
```

### Final and Const

<p>
The final and const keyword are used to declare constants. Dart prevents modifying the values of a variable declared using the final or const keyword. These keywords can be used in conjunction with the variable’s data type or instead of the var keyword.

The const keyword is used to represent a compile-time constant. Variables declared using the const keyword are implicitly final</p>

>Syntax: final Keyword

```
final variable_name
```
<p>OR</p>

```
final data_type  variable_name
```
>Syntax: const Keyword

```
const variable_name
```
<p>OR</p>

```
const data_type variable_name
```