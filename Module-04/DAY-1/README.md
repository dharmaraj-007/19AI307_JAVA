# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
Write  a Java program using copy constructor to print the perimeter of triangle.
## ALGORITHM :
STEP 1:Start the program.

STEP 2:Define the Triangle class with fields: length, breadth, and width.

STEP 3:Create two constructors in the Triangle class:

- A parameterized constructor to initialize the triangle sides.

- A copy constructor to create a new Triangle object by copying another.

STEP 4:Define a method perimeter() that returns the sum of the three sides.

STEP 5:In the main method, create the first triangle object using the parameterized constructor.

STEP 6:Create the second triangle object using the copy constructor and pass the first object.

STEP 7:Call the perimeter() method on both objects and print their perimeters.

STEP 8:End the program.
## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```

class Triangle 
 { 
         int length; 
         int breadth; 
         int width;
         Triangle (int l, int b, int w) 
         {  
             this.length=l;
             this.breadth=b;
             this.width=w;
         } 
        
         Triangle(Triangle obj) 
         { 
           this.length=obj.length;
           this.breadth=obj.breadth;
           this.width=obj.width;
           
         } 
        
        int perimeter() 
        { 
           return length+breadth+width;
        } 
 } 
        //class to create Rectangle object and calculate area 
        public class CopyConstructor 
 { 
           public static void main(String[] args) 
           { 
             Triangle  firstRect = new Triangle (4,5,6); 
            Triangle secRect=new Triangle(firstRect);
             System.out.println("Perimeter  of First Triangle : "+firstRect.perimeter());
             System.out.println("Perimeter of Second Triangle : "+secRect.perimeter());
           } 
 } 
 

```
## OUTPUT:

![image](https://github.com/user-attachments/assets/d7559f88-4c38-4378-af74-64b9587a7a05)


## RESULT:
Thus the Java program using copy constructor to print the perimeter of triangle was executed successfully.
