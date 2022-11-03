# project1_dorsu_atm_Dosono

import java.util.Scanner;
public class Main {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Welcome to DOrSU banking system.");
		System.out.println('\n');
 System.out.println("            **");
 System.out.println('\n');
 System.out.println("To start select from the following transaction:");
 System.out.println('\n');
 System.out.println("            1- View Balance");
 System.out.println("            2- Withdraw");
 System.out.println("            3- Deposit");
 System.out.println("            4- Exit");
System.out.println("--------------------------------------------------");
System.out.println("--------------------------------------------------");System.out.println('\n');
int balance = 1000;
int maintain = 100;


 System.out.print("Enter transaction NO.: ");
 int ATM = sc.nextInt();
 
 switch (ATM){
   case 1:
    System.out.println("Your balance is: "+ balance);
    break;
   case 2:
    System.out.println("Please enter the amount");
     int amount = sc.nextInt();
     int remain = balance - amount;
     if(remain < maintain){System.out.println("Make sure your balance in 100+ to complete this transition");}
    
     
     
     
     
     
     

    
  
  
  
  
  
  }


	}
}


![image](https://user-images.githubusercontent.com/69900199/199685962-9238c9e9-2adc-43cd-b699-3d4b3c6af2e2.png)
