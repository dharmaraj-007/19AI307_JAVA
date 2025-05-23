# Ex.No:6(A)  INNER CLASS
## AIM:
Write a Java Program using Method Local Inner Class 

## ALGORITHM :

1. Start the program.

2. Define the class MethodLocal with an instance variable value initialized to "Outer Class Variable".

3. Define the method display() inside MethodLocal:

- Declare a local variable value initialized to "Inner Class Variable".

- Define a method-local inner class Inner with a method print() that:

- Prints the outer class’s value using MethodLocal.this.value.

- Prints the local variable value.

4. Create an instance of the inner class Inner inside the display() method.

5. Call the print() method of the inner class instance to display both values.

6. In the main method, create an object of MethodLocal.

7. Invoke the display() method on the object to execute the print operations.

8. End the program.
## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:

```
public class MethodLocal{
    String value = "Outer Class Variable";
    public void display() {
        String value = "Inner Class Variable";
        class Inner {
            public void print() {
                System.out.println(MethodLocal.this.value); 
                System.out.println(value);
            }
        }
        Inner innerObj = new Inner();
        innerObj.print();
    }
    public static void main(String[] args) {
        MethodLocal obj = new MethodLocal();
        obj.display();
    }
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/928bcc18-581d-4aa9-abef-69f0e00744f3)


## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

