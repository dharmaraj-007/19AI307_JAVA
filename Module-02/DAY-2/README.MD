# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To demonstrate the default access modifier in Java using two classes (BaseClass and Main) by performing addition of two variables a and b, and printing the result c
## ALGORITHM :
1.Start the program.
2.Create a class named BaseClass.
3.Declare two default-access variables a = 3 and b = 5.
4.Create a default-access method display() that adds a and b, stores the result in variable c, and prints c.
5.Create a second class named Main.
6.In the main() method, create an object of BaseClass.
7.Call the display() method using the object.
8.End the program.


## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: Bala R
RegisterNumber: 212222220007
```

## Sourcecode.java:
```
class BaseClass
{
    void display()
    {
        int a=3,b=5;
        int c=a+b;
        System.out.println(c);
    }
}
public class Main{
    public static void main(String[] args){
        BaseClass obj=new BaseClass();
        obj.display();
    }
}
```

## OUTPUT:

https://github.com/Pryasaee/19AI307_JAVA/blob/f1809208ac4eec2dc86a0340921c0373d2accdb9/Module-02/DAY-2/java.png

## RESULT:
Thus the java program to display the addition number using private modifiers only was executed successfully.


