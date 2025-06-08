//Create a program to calculate installment amount for permonth -java

import java.util.Scanner;
class main{
    public static void main(String[]args){
        try(Scanner sc = new Scanner(System.in)){
            int phonePrice=1800, numberOfInstallment, installmentPermonth;
            
            System.out.print("number of installment: ");
            numberOfInstallment = sc.nextInt();
            
            installmentPermonth = phonePrice/numberOfInstallment;
            
            System.out.println("Monthly installment amount: "+installmentPermonth);
            
        }
        
    }
}
