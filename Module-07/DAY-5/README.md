# Ex.No:7(E)  POLYMORPHISM

## AIM:
To write a Java program that adds two numbers using a Thread created with the Runnable interface, taking the two integers as user input.
## ALGORITHM :
1.Import Scanner for user input.  
2.Create a class AdditionTask that implements the Runnable interface.  
3.In the AdditionTask constructor, accept two integers.  
4.In the run() method, add the two numbers and display the result.  
5.In the main() method, get user input for two integers.  
6.Create a Thread object by passing an instance of AdditionTask and start the thread.  


## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
class prog extends Thread
    {  
        Scanner sc=new Scanner(System.in);
        void display(){
        int n=sc.nextInt();
        int m=sc.nextInt();
        int v=n+m;
        System.out.print("Result: "+v);
    }
    public static void main(String args[])
    {  
        prog obj=new prog();
        obj.display();
       
     
     }  
    }
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/46a1169c-a90a-48c6-8464-376509978369)


## RESULT:

The program adds two user-input numbers in a thread created using the Runnable interface.


