# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
Write a parameterized constructor in the Student class given below that initializes the name and department as class field with the string "Antony” and "AIML".

## ALGORITHM :

1. Start the program.

2. Define the Employee class with two fields: name and dept.

3. Create a parameterized constructor in Employee to initialize name and dept using the this keyword.

4. Define two methods: getName() and getDept() to return the name and dept fields.

5. In the Sample class, define the main method.

6. Create an Employee object with "Antony" as name and "AIML" as department.

7. Call the getName() and getDept() methods, store the returned values in variables, and print them.

8. End the program.

## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
 class Employee {

	String name;
	String dept;
	public Employee(String name,String dept){
	    this.name=name;
	    this.dept=dept;
	}
	
	
	public String getName() {
	return name;
	}
	public String getDept() {
		return dept;
	}
}

public class Sample {
	
	public static void main(String[] args) {

			Employee E=new Employee("Antony","AIML");
			String std1=E.getName();
			String std2=E.getDept();
			System.out.println(std1);
			System.out.println(std2);
	}
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/1597528a-ef44-4527-bd2d-6c9466f12d69)

## RESULT:
Thus, the  java program was successfully initializes the name and department as class field with the string "Antony” and "AIML".

 


