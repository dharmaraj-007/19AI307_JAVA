# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java class Calculator with a static method powerInt(int num1, int num2) that calculates the power of the given numbers using the Math.pow() function. The class also uses a constructor to initialize a value as 0.
## ALGORITHM :
1.Create the Calculator Class:
2.Define a constructor that initializes the value as 0.
3.Define a static method powerInt(int num1, int num2) that calculates the power of num1 raised to num2 using the Math.pow() function.
4.Use the Constructor: Initialize the class with a value of 0.
5.Calculate the Power: Use Math.pow(num1, num2) to calculate the power of the two numbers.
6.Print the Result: Print the calculated result.

## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
import java.lang.Math;
public class Calculator {
    private int result;

public Calculator(int num1,int num2){
    this.result=(int)Math.pow(num1, num2);
}
public int getResult(){
    return this.result;
}
public static void main(String[] args) {
    Calculator calculator = new Calculator(10, 2);
    System.out.println(calculator.getResult());
	}
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/e677c65a-5740-4531-8276-7c516d3bf980)

## RESULT:
The Calculator class successfully calculates the power of 10 raised to 2, resulting in 100 using the static method powerInt() and the Math.pow() function.

