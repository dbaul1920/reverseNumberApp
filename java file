package NumberApp;

import java.util.Scanner;

public class ReverseNumber {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		System.out.println("Please enter a 4 digit number to reverse:");
			
		int original = scanner.nextInt();
		int reverse = 0;
		int remainder;
		
		//Run loop as long as numbers are greater than zero
		while(original !=0){
			remainder = original % 10;
		// Flip number, move over to next column, add remainder to the end 
			reverse = reverse * 10 + remainder;
		//Calls base number	
			original = original / 10;
		}
		//Display reversed number
		System.out.println("The reverse of the number is: " + reverse);
		
	}
	
	
}
