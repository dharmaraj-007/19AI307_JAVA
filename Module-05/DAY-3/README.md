# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `Employee`:
-	a) Private variables `n1` and `n2`
-	b) Method `setsum(int n1, int n2)` to set values of `n1` and `n2`
-	c) Method `getsum()` to calculate and print `sum = n1 + n2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `n1` and `n2`
-	b) Create ` Employee ` object, set values, and call `getsum()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:

```
import java.util.*;
class Amount{
    private int pri;
    private int sal;
    public void setamt(int pri,int sal){
        this.pri=pri;
        this.sal=sal;
    }
    public void getamt(){
        int res=pri+sal;
        System.out.println("Sum is "+res);
    }
}
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        Amount a=new Amount();
        int in=sc.nextInt();
        int in1=sc.nextInt();
        a.setamt(in,in1);
        a.getamt();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/572f08b4-298f-45a3-b503-cca9fb985e48)


## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






