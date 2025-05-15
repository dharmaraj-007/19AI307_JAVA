# Ex.No:6(A)  INNER CLASS
## AIM:
To demonstrate the usage of a method-local inner class in Java by creating a Department class that has an inner class Inner for displaying the department's name.
## ALGORITHM :
1.Create a Department class with a string "Financial and Management Department".  
2.Define a method display() in the Department class, which contains a method-local inner class Inner.  
3.The Inner class will have a print() method that displays the department name.  
4.In the main() method, create an object of the Department class and   
5.access both the display() and the inner class functionality.  

## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
public class Department{
    String departmentName = "Financial and Management Department";
    public void display(){
        class Inner{
            public void print(){
                System.out.println("Department is " + departmentName);
            }
        }
        Inner inner=new Inner();
        inner.print();
        System.out.println("Company is ABC Industries");
        
    }
    public static void main(String[] args){
        Department department=new Department();
        department.display();
    }
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/65277c43-0931-438b-9867-7a1fb43c20a5)


## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

