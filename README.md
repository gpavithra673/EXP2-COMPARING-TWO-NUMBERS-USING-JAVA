# EXP2-COMPARING-TWO-NUMBERS-USING-JAVA
## AIM:
### To compare two numbers using java
## PROCEDURE:
### 1.Create the main class and declare the main methoda sothat the program will be recognised by JVM to run.
### 2.Declare two variables along with proper data type.
### 3.Use 'if' consition to check their values and find the greater number.
### 4.Print the output using 'System.out.print'.
### 5.The program will be executed after compiling them.
## CODE:
```
import java.util.Scanner;
public class compare_num
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter first number: ");
        int a = sc.nextInt();
        System.out.print("Enter second number: ");
        int b = sc.nextInt();
        compare(a,b);
    }
    public static void compare(int n1,int n2)
    {
        if(n1 > n2)
        {
            System.out.println(n1+" greater than "+n2);
        }
        else if(n2 > n1)
        {
            System.out.println(n2+" greater than "+n1);
        }
        else
        {
            System.out.println("Both the numbers are equal");
        }
    }
}
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224062319-a2b55f3b-3f88-44eb-a076-e8a0a385699e.png)
## RESULT:
### Hence the program is executed successfully and the output is obtained for comparing two numbers.
