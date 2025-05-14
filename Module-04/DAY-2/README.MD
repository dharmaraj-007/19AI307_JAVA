# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create a parent class Animal with methods eat() and sleep(), and a child class Bird that inherits from Animal and adds a fly() method. The program demonstrates invoking methods from both classes using their respective instances.
## ALGORITHM :
1.Create the Animal Class:
  Define two methods eat() and sleep() in the Animal class.
2.Create the Bird Class (Child Class):
  Inherit from the Animal class.
  Define a new method fly() specific to the Bird class.
3.Create Instances:
  Instantiate an Animal object and invoke the eat() and sleep() methods.
  Instantiate a Bird object and invoke the eat(), sleep(), and fly() methods.
4.Invoke the Methods:
  Call the appropriate methods on each instance to demonstrate method invocation.


## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
class Animal{
    
   void eat(){
       System.out.println("Calling Eat Method");
   }
   void sleep(){
       System.out.println("Calling Sleep Method");
   }
}

class Bird extends Animal{
   
  void fly(){
      System.out.println("Calling Fly Method");
  }
}

public class Ans{
  public static void main(String[] args){
      
    Bird obj=new Bird();
    obj.eat();
    obj.sleep();
    obj.eat();
    obj.sleep();
    obj.fly();
    
  }
}	

```

## OUTPUT:

https://github.com/Pryasaee/19AI307_JAVA/blob/94e1b664d0113b2fa11da3b3fb97c2b746e2ad68/Module-04/DAY-2/2.png

## RESULT:
The Animal class successfully demonstrates the invocation of eat() and sleep() methods, and the Bird class extends Animal to add a fly() method, with all methods being invoked successfully using instances of each class.

