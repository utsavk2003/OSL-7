# OSL-7
 
/*Write a java program to accept two integers from the user and display result of all arithmetic operations. 
Handle the appropriate exceptions.*/
/* GITHUB OSL LAB 8 TESTING
import java.util.Scanner;
import java.util.InputMismatchException;

public class ooad1a {
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int a,b;
        try
        {
            System.out.print("\nenter a : ");
            a=sc.nextInt();
            System.out.print("enter b : ");
            b=sc.nextInt();
            System.out.println("\naddition: "+ a+b);
            System.out.println("subtraction: "+ (a-b));
            System.out.println("multiplication: "+ a*b);
            System.out.println("division: "+ a/b); 
            System.out.print("modular: " + a%b);   
        } 
        catch(ArithmeticException e)
        {
            System.out.print("\nerror! cant devide by 0\n\n");
        }
        catch(InputMismatchException e)
        {
            System.out.print("\nerror! enter an integer value\n\n");
        }
    }
    
}
