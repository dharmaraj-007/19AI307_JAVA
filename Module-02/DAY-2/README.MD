# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
Demonstrate the java program using public access modifier and find the quotient and remainder.

## ALGORITHM :
Step 1: Start

Step 2: Define a public class named Demo
Step 3: Inside the Demo class, define a public method named calculate(int a, int b)
Step 4: Compute the quotient as quo = a / b and remainder as rem = a % b


Step 5:Print "Quotient is: " followed by quo and Print "Remainder is: " followed by rem

Step 6: Define the public static void main(String[] args) method
Step 7: Inside main: Declare and initialize two integer variables:a = 15 b = 2
Create an object div of class Demo
Demo div = new Demo();
Call the public calculate() method using the object:
div.calculate(a, b);

Step 6: End








## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: Dharmaraj S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
public class Demo{
    public void calculate(int a,int b)
    {
        int quo=a/b;
        int rem=a%b;
        System.out.println("Quotient is: "+quo);
        System.out.println("Remainder is: "+rem);
    }
    public static void main(String[] args)
    {
        int a=15;
        int b=2;
        Demo div=new Demo();
        div.calculate(a,b);
    }
}
```
## OUTPUT:



## RESULT:
Thus the java program to display the addition number using private modifiers only was executed successfully.


