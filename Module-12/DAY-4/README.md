# Ex.No:12(D) JAVA QUEUE
## AIM:
To write a Java program that displays elements from a PriorityQueue, inserts a new element using the offer() method, and then displays the updated queue.

## ALGORITHM :
1.Create a PriorityQueue and add initial elements using add().  
2.Display the elements using a loop or iterator.  
3.Insert a new element using the offer() method.  
4.Display the updated elements of the PriorityQueue  

## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        
        PriorityQueue<Integer>t=new PriorityQueue<Integer>();
        Scanner sc=new Scanner(System.in);
        int size = sc.nextInt();
        for(int i=0;i<size;i++){
            t.offer(sc.nextInt());
        }
            System.out.println("Display the element of Queue:");
            System.out.println(t);
        }
    }
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/c0d68da5-ace5-4d25-91ba-3ffee01fc251)


## RESULT:
The program reads a number of integers from user input, stores them in a priority queue, and then displays the queue with elements sorted in natural ascending order.

