### Ex.No:1(E) STRINGS AND MATH FUNCTION
#### QUESTION:
Write a Java program to find the absolute value of a number using Math.abs().

### AIM:
To write a Java program that finds the absolute value of a given number using the Math.abs() method.
### ALGORITHM :
1.Start the program and create a Scanner object.

2.Read a number n (can be integer or decimal) from the user.

3.Use the built-in function Math.abs(n) to compute its absolute value.

4.Display the calculated absolute value.

5.End the program.
### PROGRAM:
/*
Program to implement variables and Operators using Java
Developed by: Jothikrishnaa V
RegisterNumber: 212223100017
*/

#### Sourcecode.java:
```java
import java.util.*;
public class demo
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        double n=sc.nextDouble();
        System.out.println("Absolute value = "+Math.abs(n));
    }
}
``` 
### OUTPUT:
![alt text](image-4.png)
### RESULT:
Therefore the program has been executed successfully.