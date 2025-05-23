# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 Write a Java Program to perform cube value using synchronization  method concept  for the below Scenario.In a Class Table create a synchronized void cube method in that perform cube operation Note :Assume Sleep as 400 ms  i.e Thread.Sleep(400)
 
## ALGORITHM :
1. Start the program.

2. Define a class named Table.

3. Inside the Table class, create a method cube(int n) to calculate and print cube values from 1 to n.

4. Use a synchronized(this) block to ensure only one thread can access the cube calculation at a time for the current object.

5. Use a for loop inside the synchronized block to iterate from 1 to n:

- Calculate the cube of the current value i.

- Print the cube in the format: "cube for range value n i: result".

7. Add a delay of 400 milliseconds between each iteration using Thread.sleep(400) for simulation.

8. End the program.


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: DHARMARAJ S
RegisterNumber:  212222240025
*/
```

## Sourcecode.java:
```
class Table
    {  
    void cube(int n){
        synchronized(this){
        for (int i=1;i<=n;i++){
            System.out.println("cube for range value "+n+" "+i+":"+(i*i*i));
        }
        try{
            Thread.sleep(400);
        }
        catch(Exception E){
            System.out.println(E);
        }
    } 
    }

}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/616b9b30-0fca-4def-977b-8638b2f02cab)


## RESULT:
Thus the java program for synchronization was executed successfully.

