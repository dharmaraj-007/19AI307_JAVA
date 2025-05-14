# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To demonstrate the "has-a" relationship in Java by creating a program that adds two numbers using classes and objects.
 
## ALGORITHM :
1.Create a class Numbers with two attributes num1 and num2.
2.Provide a method in the Numbers class to set the values of num1 and num2.
3.Create a Calculator class that has a Numbers object (demonstrating the "has-a" relationship).
4.Use the Calculator class to perform the addition by accessing the Numbers object's values.
5.In the Main class, create objects and call the methods to display the result.

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
class add{
    int sum(int a,int b){
        return (a + b);
    }
}
public class Main{
    public static void main(String[] args){
        int a,b,s;
        Scanner sc=new Scanner(System.in);
        a=sc.nextInt();
        b=sc.nextInt();
        add dd=new add();
        s=dd.sum(a,b);
        System.out.println("Sum is:"+s);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/b019c44a-39e6-4c98-adac-6559366cb821)

## RESULT:
The program prints "Sum: 30" by adding two numbers using the "has-a" relationship between the Calculator and Numbers classes.
