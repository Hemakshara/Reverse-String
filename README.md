# Reverse-String

package programs;

import java.util.Scanner;

public class reversestring {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
        System.out.println("Enter The String :");
		reversestring n1 = new reversestring();
		Scanner sc = new Scanner(System.in);
		String S = sc.nextLine();
		
		System.out.println(""+S);
		
		String reverse = "";
		for(int i=S.length()-1; i>=0; i--)
			
		{
			reverse +=  new Character(S.charAt(i));
			
			
		}
		
		System.out.println("" +reverse);
		
		
		
		
	}

}
