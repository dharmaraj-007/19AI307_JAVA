# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To write a Java program that performs cube calculation using static synchronization, ensuring that only one thread accesses the cube() method at a time, even across different instances.
## ALGORITHM :
1.Create a class Table with a static synchronized void cube(int n) method.  
2.Inside cube, compute and print the cube of the given number, with a Thread.sleep(400) to simulate delay.  
3.Create a class extending Thread, say MyThread, which calls Table.cube(n) in its run() method.  
4.In main(), create multiple threads passing different numbers and start them.  
5.Observe synchronized execution — one thread at a time accesses the cube() method.  

## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: Bala R
RegisterNumber:  212222220007
*/
```

## Sourcecode.java:
```
class Table
    {
        void cube(int n){
            synchronized(this){
                int temp=1;
                for(int i=1;i<=n;i++)
                {
                    int j=i;
                    System.out.println("cube for range value " +n+" "+i+":" + (j*j*j));
                    try
                    {
                        Thread.sleep(400);
                    }
                    catch(Exception e){
                        System.out.println(e);
                    }
                }
            }
        }
    }
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/cfa8120d-4783-48aa-a2d1-650cc08596e5)

## RESULT:
Thus the java program for synchronization was executed successfully.

