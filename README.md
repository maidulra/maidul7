# maidul7
newday

package perclass;
import java.util.Scanner;

public class Ex4 {
	  Scanner sc=new Scanner(System.in);
	  
	public static void main(String[] args) {
		// TODO Auto-generated method stub

		int bottle=0;
		int nut=0;
		int washer=0;
		
		Scanner input = new Scanner(System.in);
		
		 System.out.print("Enter the amount of bolt: ");
		 bottle= input.nextInt();
		
		 System.out.print("Enter the amount of nut: ");
		 nut= input.nextInt();
		 
		 System.out.print("Enter the amount of washer: ");
		 washer= input.nextInt();
		
		//Calculate Price for all		 
		 int bottles =5 * bottle;
		 int nuts= 3 * nut;
		 int washers=1 * washer;
		 
		 int doub=2*bottle;
		 
		 int cost = bottles + nuts+washers;
				
		 if (nut==bottle && washer == doub){
			 System.out.print("Total Cost: "+cost+" cents");
		 }else{
			 
			 if (nut!= bottle && nut < bottle){
				 System.out.print("Too Few Nuts");
			 }else if (nut!= bottle && nut > bottle) {
				 System.out.print("Too Few Bolts");
			 }
			 if (washer != doub && washer<doub){
				 System.out.print("Too Few Washer");
			 }
			 
			 
			 
			
			 
			 
			 
			 
			 
		 }
			 

			 --------------------------------------------------------------
			 
			 
			 package perclass;
import java.util.Scanner;



public class Ex1 {
	 static Scanner sc=new Scanner(System.in);

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		System.out.print("Enter the radius: ");
		
		
double radius=sc.nextDouble();
double area=Math.PI *(radius*radius);


System.out.println("the cricle area is:"+area);

double CircleArea=Math.PI*3*radius;
	}
	

}
  
----------------------------------------------------------------------

package perclass;

import java.util.Scanner;
public class ex3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		  
	     double discount=0.1;
	       int total=0;
	       
	       Scanner input = new Scanner(System.in);
		   System.out.print("Enter value of purchases: ");
		   total=input.nextInt();
   total=(int) (total-total*discount);
   if (total<1000){	
	   System.out.println("Sorry no discount");
   }
   else{
		
		 
		
		  System.out.println("Value of discounted price: "+total);
   }
   }
}

		  
		  
	


----------------------------------------------------------------------

package perclass;
import java.util.Scanner;

public class Ex2 {
	  Scanner sc=new Scanner(System.in);
	
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
		   int dollars;
	       int cents;
	       
	       String inputNumberString;
	       
	       int inputNumber;
	       int calculatedAnswer;
		
		   double dollar= /100;
	       double cent =  % 100;

	    System.out.println ("The Cents entered equal: $"+ dollars +"."+ cents);
		
		
	}

}


			 
