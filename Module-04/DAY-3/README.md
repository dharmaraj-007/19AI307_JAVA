# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `Vehicle`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Car` that extends `Vehicle`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `Vehicle` class
-	ii) Call `this.display()` to invoke `display()` from `Car` class
4.	Define `Main` class with `main` method:
-	a) Create a `Car` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End

## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
class Vehicle {
    void display() {
        System.out.println("I am a Vehicle");
    }
}
class Car extends Vehicle {
    void display() {
        System.out.println("I am a Car");
    }

    void print() {
        super.display(); 
        this.display();  
}
public class Main {
    public static void main(String[] args) {
        Student sc = new Student();
        sc.print();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/31367d3a-6fed-4293-bf5a-50bfaeb254d8)

## RESULT:
Thus the java program for constructor chaining was executed successfully.




