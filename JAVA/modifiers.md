# What is modifiers ?
#         or
# What are the various access specifiers in Java?

## In Java, access specifiers are the keywords that are used to define the access scope of a method, class, or variable.
## There are two types of ***modifiers*** or ***access specifiers*** in Java.

### The access modifiers in Java specify the accessibility or scope of a field, method, constructor, or class. We can change the access level of fields, constructors, methods, and classes by applying the access modifier to them.

## There are four types of Java ***access modifiers***:
  ### 1. public
  ### 2. default
  ### 3. private
  ### 4. ptotected

# BUT

## Class Level Access :  Only public and default(no modifier) access modifiers applicable for Top-Level classs
## Member-Level Access : Methods, constructors and variables can use all four access modifiers to control visibility.

## public
- The public access-modifier  allows access from all other classes ,it means they can be accessed from any other packages.

## default
 - The default access-modifier / no access-modifier  it allows access only within the same package packages.  It means  It cannot be accessed from outside the package. 
- When we do not specify any specifier, the default access specifier is prefixed by default.

## private 
- The private access-modifier  restrict access to the defining class only.it means It cannot be accessed from outside the class.

## protected
- The protected access modifier is accessible within the package and outside the package, but through inheritance only (/or )accessable through sub classes .

- The protected access modifier can be applied to the data member, method and constructor. It cannot be applied to the class. It provides more accessibility than the default modifier.

# non-access modifier

## In Java, non-access modifiers affect the behavior of classes, methods, and variables, but they don't control their accessibility.
## These modifiers provide additional functionalities like defining class behavior, creating constants, or managing thread-safety.

# Here's a breakdown of non-access modifiers in Java:
# Key Non-Access Modifiers:
## static:
### Indicates that a member (variable, method, or inner class) belongs to the class itself, rather than to an instance of the class. Static members can be accessed directly using the class name without creating an object. 
## final:
### Marks a variable, method, or class as immutable, meaning it cannot be changed after its initial assignment or definition. 
## abstract:
### Used to define abstract classes and methods, which cannot be instantiated directly and must be extended by subclasses that provide concrete implementations. 
## synchronized:
### Used to ensure that a method or a block of code is thread-safe, meaning only one thread can access it at a time. 
## transient:
### Indicates that a variable should not be serialized when an object is saved, meaning its value is not preserved when the object is saved. 
## volatile:
### Indicates that a variable's value can be changed by multiple threads and that the Java Virtual Machine (JVM) should ensure that changes made by one thread are visible to others. 
## native:
### Indicates that a method is implemented in a language other than Java, typically C or C++. 
## strictfp:
### Ensures that floating-point calculations are performed in a consistent way across different platforms. 

