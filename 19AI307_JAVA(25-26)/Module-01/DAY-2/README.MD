# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
Lovely has just started learning Java and is very excited about how to display messages on the screen. Her first mission is to understand how different types of print statements work:

System.out.print() → prints on the same line

System.out.println() → prints and moves to the next line

System.out.printf() → prints formatted output

## AIM:

To write a java program in datatypes,variables and operators to display a greeting message using different print statements.

## ALGORITHM :
1.	Start the program.
2.	Read the user's name as a String.
3.	Read the user's age as an integer.
4.	Read the user's favorite decimal number as a float.
5.	Use System.out.print() to print a greeting message with the name on the same line.
6.	Use System.out.println() to print the age on a new line.
7.	Use System.out.printf() to print the favorite number formatted to 2 decimal places.
8.	End the program.

## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: Abinaya A
RegisterNumber: 21223040003 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        String name=sc.next();
        int age=sc.nextInt();
        double num=sc.nextDouble();
        System.out.println("Hello, "+name);
        System.out.println("You are "+age+" years old");
        System.out.printf("Your favorite number is %.2f ",num);
    }
}
```

## OUTPUT:

<img width="772" height="395" alt="Screenshot 2025-11-14 083152" src="https://github.com/user-attachments/assets/cae6ec65-10fb-46db-9c63-db37cffa0686" />


## RESULT:
Thus , a Java program using datatypes, variables, and operators was successfully written to demonstrate the use of System.out.print(), System.out.println(), and System.out.printf() for displaying output .

