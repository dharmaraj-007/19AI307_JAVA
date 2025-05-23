# Ex.No:7(C)             THREAD IN JAVA
## AIM:
 Write a Java program to add two numbers by creating Thread using Runnable Interface.

## ALGORITHM :
1. Start the program.

2. Define a class A that implements the Runnable interface.

3. Inside class A, create a Scanner object and implement the run() method:

4. Read two integers from user input.

5. Calculate their sum.

- Print the result.

- In the main method, create an object of class A.

- Create a Thread object, passing the object of class A as a parameter.

6. Start the thread using t.start(), which calls the run() method of class A.

7. End the program after the sum is displayed.
## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: DHARMARAJ S
RegisterNumber: 212222240025 
*/
```

## Sourcecode.java:

```
import java.util.*;
class A implements Runnable{
    Scanner sc=new Scanner(System.in);
    public void run(){
        int a=sc.nextInt();
        int b=sc.nextInt();
        System.out.println("Result: "+(a+b));
    }
}
public class Main{
    public static void main(String[] args){
        A a=new A();
        Thread t=new Thread(a);
        t.start();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/64e54799-5fbd-48e4-847f-4d7f54ab6707)


## RESULT:
Thus the Java program to add two numbers by creating Thread using Runnable Interface was executed successfully






