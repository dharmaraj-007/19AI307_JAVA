# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To demonstrate inheritance by creating a parent class and a child class, where the child class inherits from the parent class, and calling the methods using objects of both classes.

## ALGORITHM :
1.Define a parent class with a method that prints "This is parent class".
2.Define a subclass that inherits from the parent class and has its own method that prints "This is child class".
3.Create an object of the parent class and call its method.
4.Create an object of the child class and call its method.
5.Create an object of the child class and call the method of the parent class using this object.

## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
class Pclass{
  public void pmethod(){
      System.out.println("This is parent class");
   
  }
}

class Cclass extends Pclass{
  public void cmethod(){
      System.out.println("This is child class");
    
  }
}

public class Ans{
  public static void main(String[] args){
      Pclass p=new Pclass();
      p.pmethod();
      Cclass c=new Cclass();
      c.cmethod();
      Cclass child=new Cclass();
      child.pmethod();
  
  }
}	
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/34d82cb6-f0c3-4a1b-a657-514ad370f0ea)

## RESULT:
The program prints "This is parent class", "This is child class", and "This is parent class" in sequence.


