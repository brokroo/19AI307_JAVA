# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true. [Class name is ‘Demo’]

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class named 'Demo'
4.	Implement the main method
5.	Create a new instance of the 'Scanner' class named 'sc' to read user input
6.	Read an integer 'a' from the user using the 'nextInt' method of 'sc'
7.	Read another integer 'b' from the user using the 'nextInt' method of 'sc'
8.	Check if 'a' is less than 50 or if 'a' is less than 'b'
a)	If the condition is true, print "true" using the 'print' method of 'System.out'
b)	If the condition is false, print "false" using the 'print' method of 'System.out'
9.	End

## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: Sanjith R
RegisterNumber: 212223230191
*/
import java.util.*;
public class Demo
{
    int a,b;
    public static void main(String[] args)
    {
        Demo obj = new Demo();
        Scanner sc=new Scanner(System.in);
        obj.a=sc.nextInt();
        obj.b=sc.nextInt();
        System.out.println(obj.a < 50 && obj.a < obj.b);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/e8161fd4-e228-4d7a-a50e-2ec6322822a8)

## RESULT:
Thus, the Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true is created successfully.
