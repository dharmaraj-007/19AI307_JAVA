# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To demonstrate class inheritance in Java by creating a GrandParent, Parent, and Child class, where each class has its own constructor, and the constructors are accessed using a Child class object.
## ALGORITHM :
1.Create a GrandParent class with a constructor that displays "Grand Parent Class".
2.Create a Parent class that extends GrandParent and has its own constructor to display "Parent Class".
3.Create a Child class that extends Parent and has its own constructor to display "Child Class".
4.In the Main class, create a Child class object and access all the constructors, displaying the respective messages.


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
class GrandParent{
    public GrandParent(){
        System.out.println("Grand_Parent Class");
    }
}
class Parent extends GrandParent{
    public Parent(){
        System.out.println("Parent Class");
    }
}
class Child extends Parent{
    public Child(){
        System.out.println("Child Class");
    }
}
public class Main{
    public static void main(String[] args){
        Child obj=new Child();
    }
}
```

## OUTPUT:

https://github.com/Pryasaee/19AI307_JAVA/blob/6d2632382624c0841acae3fc0439ccfcf3f0b050/Module-06/DAY-2/4.png


## RESULT:
Thus the java program for multi-level inheritance was executed successfully.





