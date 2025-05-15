# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To demonstrate the concept of encapsulation in Java by creating a program that adds two numbers using getter and setter methods.
## ALGORITHM :
1.Create a class Addition with two private variables to store the numbers.  
2.Provide public setter methods to set the values of the numbers.  
3.Provide a public getter method to retrieve the numbers.  
4.Create a method add() to perform the addition of the two numbers.  
5.In the main class, create an object of Addition and use the setter methods to set values, then call the add() method to perform the addition.  

## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
class Add{
    private int a;
    private int b;
    Add(int a,int b){
        this.a=a;
        this.b=b;
    }
    public int getA(){
        return a;
    }
    public int getB(){
        return b;
    }
    public void calculatePro(){
        System.out.println(a+b);
    }
}
public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        Add obj=new Add(a,b);
        obj.calculatePro();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/1678aa54-7559-4ab3-9967-6fc152aa6b0f)

## RESULT:

The program prints "Sum: 15" after adding the two numbers using encapsulation.







