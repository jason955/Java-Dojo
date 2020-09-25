# Java_Dojo
Place for learning about all things Java

ADVANCED JAVA Syllabus:

Servlets and JSPs
1. Basics of a Web application  
  What is a web application?  
  What is a web client and web server?  
  How do client and server communicate?  
  HTTP protocol basics  
  HTML language basics  
  What is a TCP/IP port, URL?  
  Need for a Web Container  
2. Web Contaner and Web Application Project Set up  
  To set up Tomcat Container on a machine  
  To set up a Servlets JSP project in Eclipse  
  To configure dependency of Servlet JSP APIs  
  Web application project struture  
3. Servlets  
  What are Servlets?  
  What can they do? Why are they needed?  
  How do Servlets look in code?  
  HTTP Methods; GET, POST, PUT, DELETE, TRACE, OPTIONS  
  GET/POST request; differences between the two  
  Servlet Lifecycle  
  Servlet Context and Servlet Config  
  Forwarding and Redirection of requests  
4. Session Management  
  What is a session?  
  Why is it required?  
  How to get a session?  
  Session information passing between client and server  
  Sesssion information passing mechanisms - Cookies, Rewriting  
  How to destroy a session  
5. JSPs  
  Introduction to JSP an dneed for JSPs  
  Basic HTML tags  
  JSP Lifecycle  
6. JSP Elements  
  Scriptlets  
  Expressions  
  Declarations  
  Significance of above elements and fitment into the JSP Lifecycle  
  What are Directives in JSP?  
  Page Directive  
  Include Driective  
  Taglib Directive  
7. JSP Tag library  
  JSP Standard Actions  
  Expression Language  
  JSTL basics and it's usage  
  Need for Custom Tag Library  
  Custom Tag Library implementation  
  Struts Framework (version 2.x)  
  
1. Basics of MVC  
  What is MVC?  
  MVC Type1 and Type2 architecture  
  Why Struts framework?  
  Struts 1 overview  
  Struts 1 and Struts 2 comparison  
2. Struts 2 Architectutre  
  Architecture Diagram explanation of following components:  
  Components of Model, Views and Controller in Struts Framework  
  Interceptors  
  Model/Action classes  
  Value Stack  
  OGNL  
  Introduction to configurations; framework and application architecture  
  Declarative and Annotations configuration approaches  
3. Struts 2 set up and first Action class  
  Download JAR files  
  Struts 2 project build up and Configuration files  
  To build Action class  
  To intercept an HTTP request via Struts2 framework using Action class  
  Defining data and business logic in Action class  
  Preparing and Forwarding control to Views  
4. Struts 2 Interceptors  
  What are Interceptors  
  Responsibilities of an Interceptor  
  Mechanism of Interceptor calling in Struts 2  
  Defining Interceptors  
  Defining Interceptor stacks  
  Defining Custom Interceptors  
5. Struts 2 Tag Library  
  Introduction to tag library of Struts 2 and it's usage  
6. Struts 2 Validations  
  Validations using Validateable interface  
  Workflow interceptor mechanism for validations  
  Validations using Validateable interface  
  Validation Framework introduction and architecture  
  Validating user input with above two mechanisms  
7. Struts 2 Tiles Frameworks  
  Introduction to Tiles in a page  
  Struts2 Tiles framework introduction  
  Defining tiles.xml file  
  Configuring pages for tiles  
  A complete Tiles example with Struts2  
  Hibernate Framework (version 3.x)  
1. Introduction  
  What is ORM principle?  
  Why ORM?  
  ORM implemenations  
2. Hibernate Architecture  
  Introduction to Hibernate  
  Hibernate Architecture  
  What are Peristent classes?  
3. Hibernate CRUD  
  Setting up Hibernate project  
  Configuring all JARs and XML files  
  Setting up connection to DB using Hibernate  
  Performing basic CRUD operations using Hibernate API  
  Object Identity; Generator type classes  
  Using SQL with Hibernate  
  Using HQL  
  Using Criteria queries  
4. Mapping Collections and Associations  
  To define sets, mas, lists in Hibernate  
  Association Mappings: 1. One to one  
  2 One to many  
  3 Many to one  
  4 Many to many  
5. Hibernate Caching  
  What is caching?  
  What are the types of caching in Hibernate?  
  Explanation of various caching mechanisms in Hibernate  
6. Using Hibernate Annotations (if time permits)  
  Sample example of using Hibernate Annotations  
  Spring Framework (version 3.x)  
    
1. Introduction to spring  
  What is Spring?  
  Spring Architecture explanation and all it's components  
2. Introduction to all modules of spring  
  Spring Bean Factory  
  Spring Application Context  
  Spring DI  
  Spring AOP  
  Spring Integration; Spring messaging, Spring JMS  
  Spring MVC  
  Spring DAO  
3. Setting up spring  
  Setting up of Spring framework  
  Download JARs  
  Configure XML files  
4. Dependency Injection  
  What is Dependency Injection?  
  How is it implemented using Spring Framework?  
  Bean Wiring mechanisms in Spring  
5. Spring AOP  
  What is Spring AOP?  
  Implementation of Spring AOP  
  
  
  
Basic Java:  

***1. Core Java Programming Introduction of Java***
  **The JDK Directory Structure**
The JDK directory is the root directory of the JDK software installation. This directory also contains copyright, README, and src.zip files, which are the source code archive file of the Java platform.
The JDK/bin directory contains the executable and command-line launchers that are defined by the modules linked to the image.
The JDK/conf directory contains the .properties, .policy, and other configuration files intended to be edited by developers, deployers, and end users.
The JDK/lib directory contains private implementation details of the runtime system. These files are not intended for external use and must not be modified.
The JDK/jmods directory contains the compiled module definitions.
The JDK/legal directory contains copyright and license files for each module.
The JDK/include directory contains C-language header files that support native-code programming with the Java Native Interface and the Java Virtual Machine (JVM) Debugger Interface.
The JRE is the root directory of the JRE software installation. This directory contains README and other JRE folders.
The JRE/bin directory contains the executable and command-line launchers that are defined by the modules linked to the image.
The JRE/conf directory contains the .properties, .policy, and other configuration files intended to be edited by developers, deployers, and end users.
The JRE/lib directory contains private implementation details of the runtime system. These files are not intended for external use and must not be modified.
The JRE/legal directory contains copyright and license files for each module.
JDK Modules
The entire JDK has been divided in to a set of modules. As a result, one can nit-pick a set according to the requirement either during compilation, build time, or during run time into a variety of configurations. The module name specific to JDK begins with "jdk". The list with descriptions is as follows (*).

  
***2. Data types and Operators***
  **Primitive Datatypes, Declarations, Ranges**
  Primitive types are the most basic data types available within the Java language. There are 8: boolean, byte, char, short, int, long, float and double. These types serve as the building blocks of data manipulation in Java.
One kind of Java statement is a declaration statement, which is used to declare a variable by specifying its data type and name. 

  **Variable Names Conventions**
  Variable names are case-sensitive. A variable's name can be any legal identifier — an unlimited-length sequence of Unicode letters and digits, beginning with a letter, the dollar sign "$", or the underscore character "_". The convention, however, is to always begin your variable names with a letter, not "$" or "_". Additionally, the dollar sign character, by convention, is never used at all. You may find some situations where auto-generated names will contain the dollar sign, but your variable names should always avoid using it. A similar convention exists for the underscore character; while it's technically legal to begin your variable's name with "_", this practice is discouraged. White space is not permitted.
Subsequent characters may be letters, digits, dollar signs, or underscore characters. Conventions (and common sense) apply to this rule as well. When choosing a name for your variables, use full words instead of cryptic abbreviations. Doing so will make your code easier to read and understand. In many cases it will also make your code self-documenting; fields named cadence, speed, and gear, for example, are much more intuitive than abbreviated versions, such as s, c, and g. Also keep in mind that the name you choose must not be a keyword or reserved word.
If the name you choose consists of only one word, spell that word in all lowercase letters. If it consists of more than one word, capitalize the first letter of each subsequent word. The names gearRatio and currentGear are prime examples of this convention. If your variable stores a constant value, such as static final int NUM_GEARS = 6, the convention changes slightly, capitalizing every letter and separating subsequent words with the underscore character. By convention, the underscore character is never used elsewhere.

  **Numeric Literals, Character Literals**
  You may have noticed that the new keyword isn't used when initializing a variable of a primitive type. Primitive types are special data types built into the language; they are not objects created from a class. A literal is the source code representation of a fixed value; literals are represented directly in your code without requiring computation. As shown below, it's possible to assign a literal to a variable of a primitive type:
```
boolean result = true;
char capitalC = 'C';
byte b = 100;
short s = 10000;
int i = 100000;
```
Integer Literals
An integer literal is of type long if it ends with the letter L or l; otherwise it is of type int. It is recommended that you use the upper case letter L because the lower case letter l is hard to distinguish from the digit 1.

Values of the integral types byte, short, int, and long can be created from int literals. Values of type long that exceed the range of int can be created from long literals. Integer literals can be expressed by these number systems:

Decimal: Base 10, whose digits consists of the numbers 0 through 9; this is the number system you use every day
Hexadecimal: Base 16, whose digits consist of the numbers 0 through 9 and the letters A through F
Binary: Base 2, whose digits consists of the numbers 0 and 1 (you can create binary literals in Java SE 7 and later)
For general-purpose programming, the decimal system is likely to be the only number system you'll ever use. However, if you need to use another number system, the following example shows the correct syntax. The prefix 0x indicates hexadecimal and 0b indicates binary:
```
// The number 26, in decimal
int decVal = 26;
//  The number 26, in hexadecimal
int hexVal = 0x1a;
// The number 26, in binary
int binVal = 0b11010;
```
Floating-Point Literals
A floating-point literal is of type float if it ends with the letter F or f; otherwise its type is double and it can optionally end with the letter D or d.

The floating point types (float and double) can also be expressed using E or e (for scientific notation), F or f (32-bit float literal) and D or d (64-bit double literal; this is the default and by convention is omitted).

double d1 = 123.4;
// same value as d1, but in scientific notation
double d2 = 1.234e2;
float f1  = 123.4f;

  **String Literals**
  
Literals of types char and String may contain any Unicode (UTF-16) characters. If your editor and file system allow it, you can use such characters directly in your code. If not, you can use a "Unicode escape" such as '\u0108' (capital C with circumflex), or "S\u00ED Se\u00F1or" (Sí Señor in Spanish). Always use 'single quotes' for char literals and "double quotes" for String literals. Unicode escape sequences may be used elsewhere in a program (such as in field names, for example), not just in char or String literals.

The Java programming language also supports a few special escape sequences for char and String literals: \b (backspace), \t (tab), \n (line feed), \f (form feed), \r (carriage return), \" (double quote), \' (single quote), and \\ (backslash).

  **Arrays(One dimensional; two- dimensional)**
  ```
int[] new_arr = new int[10]
int[][] twoD_arr = new int[10][20];
```
  **Array of Object References**
```
class Employee{
   int empId;
}
Employee[] EmployeeArray = new Employee[10];
```

  **Enumerated Data Types**
  An enum type is a special data type that enables for a variable to be a set of predefined constants. The variable must be equal to one of the values that have been predefined for it. Common examples include compass directions (values of NORTH, SOUTH, EAST, and WEST) and the days of the week.

Because they are constants, the names of an enum type's fields are in uppercase letters.

In the Java programming language, you define an enum type by using the enum keyword. For example, you would specify a days-of-the-week enum type as:
```
public enum Day {
    SUNDAY, MONDAY, TUESDAY, WEDNESDAY,
    THURSDAY, FRIDAY, SATURDAY 
}
```
You should use enum types any time you need to represent a fixed set of constants. That includes natural enum types such as the planets in our solar system and data sets where you know all possible values at compile time—for example, the choices on a menu, command line flags, and so on.

  **Non-Primitive Datatypes** 
  These data types are not actually defined by the programming language but are created by the programmer. They are also called “reference variables” or “object references” since they reference a memory location which stores the data
Strings: String is a sequence of characters. But in Java, a string is an object that represents a sequence of characters. The java.lang.String class is used to create a string object. If you wish to know more about Java Strings, you can refer to this article on Strings in Java.

Arrays: Arrays in Java are homogeneous data structures implemented in Java as objects. Arrays store one or more values of a specific data type and provide indexed access to store the same. A specific element in an array is accessed by its index. If you wish to learn Arrays in detail, then kindly check out this article on Java Arrays.

Classes: A class in Java is a blueprint which includes all your data.  A class contains fields(variables) and methods to describe the behavior of an object.

Interface: Like a class, an interface can have methods and variables, but the methods declared in interface are by default abstract (only method signature, no body).


  **Upcasting and downcasting**

Upcasting: Upcasting is the typecasting of a child object to a parent object. Upcasting can be done implicitly. Upcasting gives us the flexibility to access the parent class members but it is not possible to access all the child class members using this feature. Instead of all the members, we can access some specified members of the child class. For instance, we can access the overridden methods.
Downcasting: Similarly, downcasting means the typecasting of a parent object to a child object. Downcasting cannot be implicitly.
Example: Let there be a parent class. There can be many children of a parent. Let’s take one of the children into consideration. The child inherits the properties of the parent. Therefore, there is an “is-a” relationship between the child and parent. Therefore, the child can be implicitly upcasted to the parent. However, a parent may or may not inherits the child’s properties. However, we can forcefully cast a child to a parent which is known as downcasting. After we define this type of casting explicitly, the compiler checks in the background if this type of casting is possible or not. If it’s not possible, the compiler throws a ClassCastException.

***3. Control Flow statements***
```public class Test {
   public static void main(String args[]) {
      int [] numbers = {10, 20, 30, 40, 50};
      for(int x : numbers ) {
         if( x == 30 ) {
            continue;
         }
         System.out.print( x );
         System.out.print("\n");
      }
   }
}
```
  The continue Statement; labelled continue statement: prints 10, 20, 40, 50
  The break Statement; labelled break statement: if continue is replaced prints 10, 20

***4. OOPS and its application in Java***
**Abstract**
Hiding the internal implementation of the feature and only showing the functionality to the users. i.e. what it works (showing), how it works (hiding)
**Interface**
Like a class, an interface can have methods and variables, but the methods declared in an interface are by default abstract (only method signature, no body).  
Interfaces specify what a class must do and not how. It is the blueprint of the class.
An Interface is about capabilities like a Player may be an interface and any class implementing Player must be able to (or must implement) move(). So it specifies a set of methods that the class has to implement.
If a class implements an interface and does not provide method bodies for all functions specified in the interface, then the class must be declared abstract.
A Java library example is, Comparator Interface. If a class implements this interface, then it can be used to sort a collection.

**Abstracts vs Interfaces**

Type of methods: Interface can have only abstract methods. Abstract class can have abstract and non-abstract methods. From Java 8, it can have default and static methods also.
Final Variables: Variables declared in a Java interface are by default final. An abstract class may contain non-final variables.
Type of variables: Abstract class can have final, non-final, static and non-static variables. Interface has only static and final variables.
Implementation: Abstract class can provide the implementation of interface. Interface can’t provide the implementation of abstract class.
Inheritance vs Abstraction: A Java interface can be implemented using keyword “implements” and abstract class can be extended using keyword “extends”.
Multiple implementation: An interface can extend another Java interface only, an abstract class can extend another Java class and implement multiple Java interfaces.
Accessibility of Data Members: Members of a Java interface are public by default. A Java abstract class can have class members like private, protected, etc.
  Consider using abstract classes if any of these statements apply to your situation:

In java application, there are some related classes that need to share some lines of code then you can put these lines of code within abstract class and this abstract class should be extended by all these related classes.
You can define non-static or non-final field(s) in abstract class, so that via a method you can access and modify the state of Object to which they belong.
You can expect that the classes that extend an abstract class have many common methods or fields, or require access modifiers other than public (such as protected and private).
Consider using interfaces if any of these statements apply to your situation:

It is total abstraction, All methods declared within an interface must be implemented by the class(es) that implements this interface.
A class can implement more than one interface. It is called multiple inheritance.
You want to specify the behavior of a particular data type, but not concerned about who implements its behavior.
 
  **extends (Abstract) and implements(interfact) keywords in Java**
 **Super class and Sub class**
  Superclass the class with which the subclass is derived from
    
 **Concrete classes in Java**
  implementation for all of its methods. They cannot have any unimplemented methods. It can also extend an abstract class or implement an interface as long as it implements all their methods. It is a complete class and can be instantiated.
  **Polymorphism**
  Polymorphism is the ability of an object to take on many forms. The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object.

Any Java object that can pass more than one IS-A test is considered to be polymorphic. In Java, all Java objects are polymorphic since any object will pass the IS-A test for their own type and for the class Object.
  
  **Compile time polymorphism -- Overloading of methods**
  Two or more methods that have different parameters
  **Run time polymorphism -- Overriding of methods**
  When a subclass redefines one of a superclasses methods
  **Method Overriding rules and method overloading rules**
  Overriding Rules:
  1. The argument list should be exactly the same as that of the overridden method.
2. The return type should be the same or a subtype of the return type declared in the original overridden method in the superclass.
3. The access level cannot be more restrictive than the overridden method's access level. For example: If the superclass method is declared public then the overridding method in the sub class cannot be either private or protected.
4.Instance methods can be overridden only if they are inherited by the subclass.
5. A method declared final cannot be overridden.
6. A method declared static cannot be overridden but can be re-declared.
7.If a method cannot be inherited, then it cannot be overridden.
A subclass within the same package as the instance's superclass can override any superclass method that is not declared private or final.
8. A subclass in a different package can only override the non-final methods declared public or protected.
An overriding method can throw any uncheck exceptions, regardless of whether the overridden method throws exceptions or not. However, the overriding method should not throw checked exceptions that are new or broader than the ones declared by the overridden method. The overriding method can throw narrower or fewer exceptions than the overridden method.

Overloading rules:
Two methods will be treated as overloaded if both follow the mandatory rules below:
1. Both must have the same method name.
2. Both must have different argument lists.
And if both methods follow the above mandatory rules, then they may or may not:
1. Have different return types.
2. Have different access modifiers.
3. Throw different checked or unchecked exceptions.
4. Constructors cannot be overridden.

  **Introduction to Object class and it's methods**
  Object class is the superclass of all Java classes. All Java classes inherited from this class. This makes it possible that we can have methods that are available in all Java classes. This simplifies things compared to C++ where this is not the case.
  ```
  boolean equals( Object o );	Gives generic way to compare objects
Class getClass();	The Class class gives us more information about the object
int hashCode();	Returns a hash value that is used to search objects in a collection
void notify();	Used in synchronizing threads
void notifyAll();	Used in synchronizing threads
String toString();	Can be used to convert the object to String
void wait();	Used in synchronizing threads
protected Object clone() throws CloneNotSupportedException ;	Return a new object that are exactly the same as the current object
protected void finalize() throws Throwable;	This method is called just before an object is garbage collected
```
  **Encapsulation**
  Encapsulation in Java is a mechanism of wrapping the data (variables) and code acting on the data (methods) together as a single unit. In encapsulation, the variables of a class will be hidden from other classes, and can be accessed only through the methods of their current class. Therefore, it is also known as data hiding.
To achieve encapsulation in Java −
1. Declare the variables of a class as private.
2. Provide public setter and getter methods to modify and view the variables values.
Benefits of Encapsulation
The fields of a class can be made read-only or write-only.
A class can have total control over what is stored in its fields.
  Java Bean, POJO  
  Getters/Setters  
  Memory management in Java  
  Heap  
  Stack  
5. Packages  
  Need for packages  
  What are packages; package declaration in Java  
  Import statement in Java  
  How do packages resolve name clashes?  
6. Miscellaneous  
  Var-Args  
  Reference variables, local variables, instance variables  
  Memory allocations to variables  
  Double equals operator(==) operator for primitives and objects  
  toString() method on an object  
7. Statics  
  Static variables and methods  
  Static imports  
  Static initialization blocks; instance intialization blocks  
  Static concept in inheritance  
8. Constructors  
  What are Constructors?  
  Properties of Constructors  
  Default and Parameterized Constructors  
  Rules for constructor implementation  
  Constructor Chaining  
  this call; super call for constructors  
  Constructors for Enumerated Data Types  
  Constructors concept for Abstract classes and interfaces  
9. Exceptions in Java  
  What are Exceptions?  
  Need for exceptions  
  How can Exceptions be coded in Java?  
  API heirarchy for Exceptions  
  Types of Exceptions  
  Keywords in Exception API: try, catch, finally, throw, throws  
  Rules for coding Exceptions  
  Declaring Exceptions  
  Defining and Throwing Exceptions  
  Errors and Runtime Exceptions  
  Custom Exception  
  Assertions  
  What are Assertions?  
  Enabling and disabling assertions in development environment  
10. Strings in Java  
  What are Strings?  
  String heap memory and Constant Pool memory  
  Immutability in Strings  
  String creation on heap and constant pool  
  Method APIs on String; operations on Strings  
  Mutability of String Objects - StringBuilder and StringBuffer  
  Splitting of Strings and StringTokenizer class  
11. Collection Framework in Java  
  The Collections Framework  
  The Set Interface  
  Set Implementation Classes  
  The List Interface  
  List Implementation Classes  
  The Map Interface  
  Map Implementation Classes  
  Queue Interface  
  Queue Implmentation classes  
  Utility classes  
  Sorting collections using utility methods  
  equals() and hashCode contract in Java collections  
  overriding equals and hashCode methods in Java  
  New Collections added in Java 1.6  
  Primitive wrapper classes and all its method APIs  
12. Generics  
  Generics for Collections  
  Generics for class  
  Generics for methods  
13. Input-Output in Java  
  What is a stream?  
  Overview of Streams  
  Bytes vs. Characters  
  Overview of the entire Java IO API  
  Reading a file; writing to a file usinf various APIs  
  Reading User input from console  
  PrintWriter Class  
14. Serialization  
  Object Serialization  
  Serializable Interface  
  Serialization API  
  ObjectInputStream and ObjectOutput  
  Transient Fields  
  readObject and writeObject  
15. Inner Classes  
  Inner Classes  
  Member Classes  
  Local Classes  
  Anonymous Classes  
  Static Nested Classes  
16. Threads in Java  
  Non-Threaded Applications  
  Threaded Applications  
  Process based multitasking Vs Thread based multitasking  
  Thread API in Java  
  Creating Threads  
  States of a Thread  
  Sychronization for threads; static and non-static synchronized methods; blocks; concept of object and class locks  
  Coordination between threads - wait, notify and notifyAll methods for inter-thread communication  
17. Applets  
  What are applets?  
  Need for Applets  
  Different ways of running an applet program  
  Applet API heirarchy  
  Life Cycle of an applet  
  Even Handlers for applets, mouse events, click events  
18. Swing GUI  
  Introduction to AWT  
  Introduction to Swing GUI  
  Advantages of Swing over AWT  
  Swing API  
  Swing GUI Components  
  Event Handlers for Swing  
  Sample Calculator application using Swing GUI and Swing Event handling  
19. JDBC  
  What is JDBC; introduction  
  JDBC features  
  JDBC Drivers  
  Setting up a database annd cretaing a schema  
  Writing JDBC code to connect to DB  
  CRUD Operations with JDBC  
  Statement types in JDBC  
  Types of Rowset, ResultSet in JDBC  
20. Access Modifers in Java  
  What are access modifiers?  
  Default  
  Protected  
  Private  
  Public  
21. Debugging of Java Programs in Eclipse.  



