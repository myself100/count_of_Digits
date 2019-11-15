# count_of_Digits

import java.util.Scanner;
public class countofDigits {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner s=new Scanner(System.in);
		long n=s.nextInt();
		long y=print(n);
		System.out.print(y);                                                       ////functioning returing count
	}
	public static long print(long n) {
		if(n<10) 
			return n; 
		else {
			return (1 + print(n/10));                                               ////calling function
		}
	}
}


output::
147258369
9
