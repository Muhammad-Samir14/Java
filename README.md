# Java
Basics Of Java
By MUHAMMAD SAMIR

What is Java?
Java is a high-level, object-oriented programming language.
It is platform-independent (write once, run anywhere).
It is used for desktop apps, mobile apps (Android), web apps, games, enterprise software, etc.

2. Features of Java
Simple → Easy to learn, similar to C++ but with less complexity.
Object-Oriented → Everything is based on classes and objects.
Platform Independent → Java programs run on the JVM (Java Virtual Machine).
Secure → No direct memory access like C/C++.
Robust → Strong memory management, error handling.
Multithreaded → Supports multiple tasks running at once.
Portable → Code can run anywhere with JVM installed.

3. Java Program Structure
Every Java program has:
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
Explanation:
class HelloWorld → Defines a class.
public static void main(String[] args) → Entry point of the program.
System.out.println("Hello, World!"); → Prints text to the screen.

4. Basic Syntax
Case-sensitive → Hello ≠ hello.
Class names → Start with uppercase (MyClass).
Method names → Start with lowercase (printData).
Statements → End with ;.
Braces { } → Group code blocks.

5. Data Types in Java
Primitive Types:
int → whole numbers (e.g., 10)
double → decimals (e.g., 3.14)
char → single character (e.g., 'A')
boolean → true/false
byte, short, long, float → other number types

Example:
int age = 20;
double price = 99.99;
char grade = 'A';
boolean isJavaFun = true;

6. Variables
Local Variables → Declared inside methods.
Instance Variables → Belong to objects.
Static Variables → Shared by all objects.

7. Operators
Arithmetic → + - * / %
Relational → == != > < >= <=
Logical → && || !

Example:
int a = 5, b = 10;
System.out.println(a + b);  // 15
System.out.println(a > b);  // false

8. Control Statements
If-Else:
if (age >= 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}

Loops:
// For loop
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}

// While loop
int j = 1;
while (j <= 5) {
    System.out.println(j);
    j++;
}

9. Functions (Methods)
public class Calculator {
    // Method with return
    public int add(int a, int b) {
        return a + b;
    }

    // Method without return
    public void greet() {
        System.out.println("Hello!");
    }
}

10. Object-Oriented Basics
Class = Blueprint
Object = Instance of class
Encapsulation = Wrapping data + methods together
Inheritance = Reusing code (child class from parent class)
Polymorphism = One name, many forms (method overloading/overriding)

Abstraction = Hiding details, showing only essentials
