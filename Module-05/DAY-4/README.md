# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :

1. Start the program.

2. Define a class Fact with a method calFact(int num) to calculate the factorial.

3. In calFact() method, initialize a variable fac = 1.

4. Use a for loop from 1 to num, multiplying fac by each value of i.

5. Return the calculated factorial value from the method.

6. In the main method, read an integer input from the user using Scanner.

7. Call calFact() with the input value, store the result, and print the factorial.

8. End the program.


## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:

```
import java.util.*;
class Fact{
    public int calFact(int num){
        int fac=1;
        for(int i=1;i<=num;i++){
            fac*=i;
        }
        return fac;
    }
}
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        Fact f=new Fact();
        int in=sc.nextInt();
        int res=f.calFact(in);
        System.out.println("Factorial is:"+res);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/05481312-2f5f-4dff-84ae-ae216e3c882a)


## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
