# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
Demonstrate the java program using public access modifier and find the quotient and remainder.

## ALGORITHM :
```
STEP 1:Define a public class Demo.

STEP 2:nside the class, create a public method calculate(int a, int b) to compute quotient and remainder:

STEP 3:Calculate quotient and remainder 

STEP 4:Print the quotient and remainder.

STEP 5:Define the public static main method as the program entry point.

STEP 6:In main, declare and initialize two integers a = 15 and b = 2.

STEP 7:Create an object of Demo and call the public calculate(a, b) method to display results.

```
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


