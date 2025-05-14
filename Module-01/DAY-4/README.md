# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To write a Java program to calculate and print the area of a square using an instance method named calculateArea() inside a class named Area. The program should use a local variable for calculation, and the method should have a void return type.

## ALGORITHM :
1.	Start the program.
2.Define a class named Area.
3.Inside the class, define an instance method named calculateArea().
4.In this method:
Use a Scanner to take user input for the side of the square.
5.Declare a local variable to store the side length.
6.Calculate the area using the formula area = side × side.
7.Print the area.
8.In the main method:
9.Create an object of class Area.
10.Call the calculateArea() method using the object.
11.End the program.

## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Area {
        void calculateArea()
    {
        double side,cirarea;
        Scanner sc=new Scanner(System.in);
        side=sc.nextDouble();
        cirarea=side*side;
        System.out.println("Area of Square is "+cirarea);
    }
    public static void main(String[] args){
        Area obj=new Area();
        obj.calculateArea();
    }
    
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/930958bd-7353-4b20-9504-2bbe133cf195)


## RESULT:
Thus, the Java program to calculate and print the area of a square using an instance method and user input was successfully executed

