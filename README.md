package com.practiceex;
import java.util.Scanner;
public class StringCharacterCount {

	public static void main(String[] args) {
		 Scanner sc=new Scanner(System.in);
		 System.out.println("Enter a String ");
		 String input=sc.nextLine();
		 
		
		 int  CharacterCount= input.length(); // (Trupti@2015)
		 System.out.println("Total number of character:"+ CharacterCount);
         sc.close();
	}

}
