# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To create a Person class with getter and setter methods for the age attribute, and use it in the Main class to print the age of a person.
## ALGORITHM :
1.Define the Person class with a private attribute age.  
2.Provide setter and getter methods for the age attribute.  
3.In the Main class, create an object of the Person class.  
4.Use the setter method to set the age and the getter method to retrieve and print the age.  


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
class Person{
    private int age;
    public int getAge(){
        return age;
    }
    public void setAge(int age){
        this.age=age;
    }
}
public class Main{
    public static void main(String[] args){
        Person p1=new Person();
        p1.setAge(24);
        System.out.println("My age is " + p1.getAge());
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e53447f2-86f1-409a-aca4-dccc35719f08)

## RESULT:
The program prints "Age of person: 25" by accessing the age value using the getter and setter methods in the Person class.






