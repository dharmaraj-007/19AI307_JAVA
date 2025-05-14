# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To write a Java program that takes an integer input from the user and determines whether the number is positive or negative.
## ALGORITHM :
1.Start
2.Create a Scanner object to take user input.
3.Prompt the user to enter an integer.
4.Read the integer input and store it in a variable num.
5.Check if num is less than 0:
     If true, print "num is Negative".
     Else, print "num is Positive".
6.End

## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Demo{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int num;
        num=sc.nextInt();
        if(num<0)
        System.out.println(num+ " is Negative");
        else
        {
            System.out.println(num + " is Positive");
        }
    }
}

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/20827b71-7530-4573-88b1-50ec6dea9118)

## RESULT:
Thus, the Java program to check whether a number is positive or negative was successfully executed.
