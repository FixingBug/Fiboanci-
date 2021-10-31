# Fiboanci-
import java.util.Scanner;

public class Fiboanci {

	public static void main(String[] args) {
		
		int a=0,b=1;
		
		Scanner sc=new Scanner(System.in);
		
		
		//System.out.print("enter the no:");
		
		int n=sc.nextInt();
		
		System.out.print(a+" "+b+" ");
		
		for(int i=2;i<n;i++) {
			
			int c=a+b;
			a=b;
			b=c;
			
			System.out.print(c+" ");
			
		}

	}
