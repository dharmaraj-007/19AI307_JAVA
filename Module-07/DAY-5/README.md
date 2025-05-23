# Ex.No:7(E)  THREAD IN JAVA

## AIM:
Write a Java program to add two numbers by creating Thread using Runnable Interface.

## ALGORITHM :
1. Start the program.

2. Create a class Multi that implements the Runnable interface.

3. Inside the run() method of Multi:

- Create a Scanner object.

- Read two integer values from the user.

- Calculate and print the sum of the two numbers.

4. In the main method, create an object of the Multi class.

5. Create a Thread object, passing the Multi object to its constructor.

6. Start the thread using start() so that it executes the run() method in a separate thread.

7. End the program after displaying the result.

## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
  import java.util.*;
class Multi implements Runnable{
    Scanner sc=new Scanner(System.in);
    public void run(){
        int a=sc.nextInt();
        int b=sc.nextInt();
        System.out.println("Result: "+(a+b));
    }
} 
        
        
public class Main{   
    public static void main(String args[])
    {  
     Multi m=new Multi();
     Thread t=new Thread(m);
     t.start();
     }  
    }  
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/eae61acc-6850-4c20-9c23-829c8900b2b1)


## RESULT:

Thus the  java program successfully to add two numbers by creating Thread using Runnable Interface.


