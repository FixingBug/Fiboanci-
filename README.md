import java.util.*;
class fab{
	public static void main(String args[]){
		Scanner input = new Scanner(System.in);
		System.out.print("Enter a number");
		int num = input.nextInt();
		int a = 0;
		int b = 1;
		int answer;
		System.out.print(a+" "+b);
		System.out.println("Fabbiancci series of "+ num + "is : ");
		for(int i=2;i<num;i++){
		answer = a+b;
		System.out.print(answer+" ");
			a =b;
			b = answer;
			

		}
}
}	
© 2021 GitHub, Inc.
Terms
