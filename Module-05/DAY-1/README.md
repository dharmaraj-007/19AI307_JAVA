# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
Write a java program to display the rank of the student.rank data should given in private with the help of setter and getter method display the rank

## ALGORITHM :

1.Start the program.

2.Define a class Rank with a private integer variable ran to store the rank.

3.Create a method setran(int a) to assign the given value to the variable ran.

4.Create a method getran() to return the value of the variable ran.

5.Define the Main class with the main() method.

6.Create an object of the Rank class and use setran(1022) to assign a rank.

7.Call getran() to retrieve the rank and print it using System.out.println.

8.End the program.
## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
class Rank{
    private int ran;
    public void setran(int a){
        ran=a;
    }
    public int getran(){
        return ran;
    }
}
public class Main{
    public static void main(String[] args){
        Rank a=new Rank();
        a.setran(1022);
        System.out.println("Student rank is "+a.getran());
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/43c48db6-1fd8-4c80-b109-275da849bf21)

## RESULT:
Thus , the  java programto display the rank of the student.rank data should given in private with the help of setter and getter method display the rank executed successfully.
