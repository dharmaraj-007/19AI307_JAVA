# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



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
class Student {
    String name = "John";
    String address = "Chennai";
}
public class Test {
    public static void main(String[] args) {
        Student obj = new Student();
        System.out.println("Name: " + obj.name);
        System.out.println("Address: " + obj.address);
    }
}
```




## OUTPUT:

![image](https://github.com/user-attachments/assets/49f0cbec-0e16-4b41-82ec-54f83f0bd62b)


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
