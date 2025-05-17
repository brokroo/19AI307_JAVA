# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End

## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: SANJITH.R
RegisterNumber: 212223230191 
*/
import java.util.*;
class prog{
    public static void main(String[] args)
    {
        int num;
        Scanner sc = new Scanner(System.in);
        num=sc.nextInt();
        if (num==0)
        System.out.println("Given number is Zero");
        else
        System.out.println(num+" is Non-Zero");
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/520493d7-a0d1-4799-87a1-21606d598045)

## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.
