# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
Write a Java Program for Animal Class have constructor to display "Animal is the Base Class".Dog Class constructor call its parent constructor and display "Dog is the Derived Class of Animal".Cat Class constructor call its parent constructor and display "Cat is the Derived Class of Animal".In Main class create object for Child class and access its corresponding Constructor

## ALGORITHM :

1. Start the program.

2. Define the base class Animal with a constructor that prints "Animal is the Base Class".

3. Define the derived class Dog that extends Animal. In its constructor, call super() to invoke the base class constructor, then print "Dog is the Derived Class of Animal".

4. Define the derived class Cat that extends Animal. In its constructor, call super() and then print "Cat is the Derived Class of Animal".

5. In the main method, create an object of the Dog class.

6. Create an object of the Cat class.

7. Observe the output showing the constructor call order and printed messages.

8. End the program.

## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:

```
class Animal{
    Animal(){
        System.out.println("Animal is the Base Class");
    }
}
class Dog extends Animal{
    Dog(){
        super();
        System.out.println("Dog is the Derived Class of Animal");
    }
}
class Cat extends Animal{
    Cat(){
        super();
        System.out.println("Cat is the Derived Class of Animal");
    }
}
public class Main{
    public static void main(String[] args){
        Dog d=new Dog();
        Cat c=new Cat();
    }
}
```

## OUTPUT:


![image](https://github.com/user-attachments/assets/c7e5a1ea-3484-4585-ad57-b817cbbbc7d3)


## RESULT:

Thus, the java program was  executed successfully 
