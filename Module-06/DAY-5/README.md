# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To implement a Regular Inner Class in Java where the Employee class has private members and the Salary class (inner class) calculates and displays the employee's salary along with their details.

## ALGORITHM :
1.Create the Employee class with private members Emp_Id and Emp_Name.  
2.Create an inner class Salary within the Employee class.  
3.Define private float members Basic and Allowance in the Salary class.  
4.Implement a public method display() in the Salary class to print the employee details and calculated salary.  
5.In the main() method, create objects of both Employee and Salary, and invoke the display method to show the information.  


## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```
class Employee{
    String Emp_Id;
    String Emp_Name;
    double Salary;
    Employee(String Emp_Id,String Emp_Name,double Salary){
        this.Emp_Id=Emp_Id;
        this.Emp_Name=Emp_Name;
        this.Salary=Salary;
    }
    public void display(){
        System.out.println(Emp_Id+" "+Emp_Name+" "+Salary);
    }
}
public class Main{
    public static void main(String[] args){
        Employee obj=new Employee("EMP123","John",24800.0);
        obj.display();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/d5521095-f9ec-4244-b9bf-01880a2c1582)


## RESULT:

Thus, the java program demonstrates regular inner class and successfully .
