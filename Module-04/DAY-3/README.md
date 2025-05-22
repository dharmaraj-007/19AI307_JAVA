# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
STEP 1:Start the program.

STEP 2:Define the base class Sports with a constructor that prints "Sports Class".

STEP 3:Create a subclass Indoor that extends Sports and calls super() to invoke the Sports constructor, then prints "Indoor Games Class".

STEP 4:Create another subclass Chess that extends Indoor, calls super() to invoke the Indoor constructor, and prints "Chess Class".

STEP 5:Define the Main class with the main method.

STEP 6:Create an object of Chess inside main, which triggers constructor chaining:

- Chess() → Indoor() → Sports().

STEP 7:Each constructor prints a message, so the output displays messages from all three classes in the order of inheritance.

STEP 8:End the program.

## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:

```
class Sports {
Sports(){
    System.out.println("Sports Class");
}
  
  }


class Indoor extends Sports {
    Indoor(){
super();
  System.out.println("Indoor Games Class");
  }
}
class Chess extends Indoor {
Chess(){
 super();
 System.out.println("Chess Class");
  }
}
public class Main {
  public static void main(String[] args) {
   Chess ch=new Chess();
  }
}
```

## OUTPUT:



## RESULT:
Thus the java program for constructor chaining was executed successfully.




