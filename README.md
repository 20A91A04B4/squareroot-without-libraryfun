package Pack1;
import java.util.*;
public class Sqrt_without_function {
	public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
System.out.println("enter number");
int n = sc.nextInt();
float sqrt , t=0;
sqrt = n/2; 
if (n == 1)
	System.out.println("Square root of "+n+" is "+n);
else
{
while(sqrt != t) // 4.0 != 4.0 
{
	t = sqrt;// t =  4.0
	sqrt = (n/t + t)/2;
}
System.out.println("Square root of "+n+" is "+sqrt);
	}
	}
}
