# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Define `Cylinder` class:
-	a) Private variables `radius` and `height`
-	b) `setRadius(int r)` and `setHeight(int h)` methods to set values
-	c) `getVolume()` method:
- i) Calculate and print `volume = pi * radius * radius * height`
3.	In `Main` class `main` method:
-	a) Use `Scanner` to read `radius` and `height`
-	b) Create `Cylinder` object, set values, and call `getVolume()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: Bala R
RegisterNumber: 212222220007
*/
```

## Sourcecode.java:
```import java.util.*;
class Cylinder{
    private double radius;
    private double height;
    public void setRadius(double radius){
        this.radius=radius;
    }
    public void setHeight(double height){
        this.height=height;
    }
    public double getVolume(){
        double pi=22.0/7.0;
        return pi*radius*radius*height;
    }
}
public class CyclinderVolume{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        Cylinder cylinder = new Cylinder();
        double radius=sc.nextDouble();
        cylinder.setRadius(radius);
        double height=sc.nextDouble();
        cylinder.setHeight(height);
        System.out.println("volume of Cylinder is: "+cylinder.getVolume());
        
    }
}
```

## OUTPUT:

https://github.com/Pryasaee/19AI307_JAVA/blob/3cd6cd0f4bd287645a9a3ade912f7f07f1530928/Module-05/DAY-2/s.png

## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.



