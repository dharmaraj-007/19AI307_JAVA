# Ex.No:7(C)             THREAD IN JAVA
## AIM:
 To Develop a Java program to create Thread using Thread class.

## ALGORITHM :
1.Import Scanner class for user input.  
2.Get the current thread using Thread.currentThread().  
3.Read the thread name from the user using Scanner.  
4.Set the thread's name using setName().  
5.Set the thread's priority to 2 using setPriority(2).  
6.Display the updated thread name and priority.  

## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:

```
import java.util.*;
public class A implements Runnable{
    public void run(){
        System.out.println(Thread.currentThread());
    }
    public static void main(String[] args){
        A a=new A();
        Scanner sc=new Scanner(System.in);
        String thname=sc.nextLine();
        Thread t=new Thread(a, thname);
        t.setPriority(2);
        System.out.println("Priority of Thread: "+t.getPriority());
        System.out.println("Name of Thread: "+t.getName());
        t.start();
    }
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/01d86686-a548-4348-8559-4a0b51b7c6d1)

## RESULT:
Thus the Java program for the creation of Thread using Thread class was executed successfully.







