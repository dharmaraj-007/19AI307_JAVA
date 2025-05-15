# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
To implement method overloading in Java by creating two methods named display—one to display integer values and another to display double values

## ALGORITHM :
1.Define a class named OverloadDemo.  
2.Create display(int a, int b) method to print two integers.  
3.Create display(double x, double y) method to print two doubles.  
4.In the main() method, create an object of OverloadDemo and   
5.call both overloaded display methods with respective arguments.  

## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
class Example{
    void disp(int num1, int num2){
        System.out.println("Arguments:" + num1 + ","+num2);
    }
    void disp(double num){
        System.out.println("\nArgument:" + num);
    }
}
public class Main{
    public static void main(String[] args){
        Example obj=new Example();
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        Double d=sc.nextDouble();
        obj.disp(a,b);
        obj.disp(d);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/d77eb12d-397f-42d6-b57c-7bb035868960)


## RESULT:
The program displays integer and double values using method overloading.


