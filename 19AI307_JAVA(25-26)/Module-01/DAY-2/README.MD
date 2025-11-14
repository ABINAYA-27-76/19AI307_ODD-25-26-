# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
In a haunted house, lights turn on or off based on the hour of entry:

If the hour is even and between 2 and 6 (inclusive), lights flicker.

If the hour is odd and between 7 and 11, lights stay off.

If the hour is 12, lights turn red.

Otherwise, the house is dark.

## AIM:
To write a Java program using conditional statements to decide light behavior based on the hour of entry.


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the hour of entry as an integer.
4.Check if the hour is even and between 2 and 6.
5.If true, print "Lights Flicker".
6.Otherwise, check if the hour is odd and between 7 and 11.
7.If true, print "Lights Stay Off".
8.Otherwise, check if the hour is 12.
9.If yes, print "Lights Turn Red".
10.If none of the above conditions match, print "The House is Dark".
11.End the program.

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Abinaya A
RegisterNumber: 212223040003 
*/
```

## SOURCE CODE:
```
import java.util.*;
public class Demo
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
       if (a >= 2 && a <= 6 && a % 2 == 0) {
            System.out.println("Lights flicker");
        } else if (a>= 7 && a <= 11 && a % 2 != 0) {
            System.out.println("Lights off");
        } else if (a == 12) {
            System.out.println("Lights red");
        } else {
            System.out.println("Dark house");
        }
    }
}
```







## OUTPUT:



## RESULT:
Thus, the Java program to implement conditional statements based on the haunted house light rules was successfully written, executed, and verified.
