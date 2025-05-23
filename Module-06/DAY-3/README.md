# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
 Write a Java Program for Media Class have constructor to display "Parent Class is Media".Magazine Class constructor call its parent constructor and display "Magazine is the one of the Child of Media Class".Channel Class constructor call its parent constructor and display "Channel is the one of the Child of Media Class".In Main class create object for Child class and access its corresponding Constructor


## ALGORITHM :
1. Start the program.

2. Define the parent class Media with a constructor that prints "Parent Class is Media".

3. Define the child class Magazine that extends Media. In its constructor, call super() to invoke the parent constructor, then print "Magazine is the one of the Child of Media Class".

4. Define another child class Channel that extends Media. In its constructor, call super() and then print "Channel is the one of the Child of Media Class".

5. In the main method, create an object of the Magazine class.

6. Create an object of the Channel class.

7. Observe the output showing the order of constructor calls and printed messages.

8. End the program.
## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:

```
class Media {
    Media() {
        System.out.println("Parent Class is Media");
    }
}
class Magazine extends Media {
    Magazine() {
          super(); 
        System.out.println("Magazine is the one of the Child of Media Class");
    }
}

class Channel extends Media {
    Channel() {
        super(); 
        System.out.println("Channel is the one of the Child of Media Class");
    }
}
public class Main {
    public static void main(String[] args) {
        Magazine magazine = new Magazine();
        Channel channel = new Channel();
    }
}

```



## OUTPUT:

![image](https://github.com/user-attachments/assets/66e079a6-8028-4185-9b15-e48144ac264e)

## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.






