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
			 

			 
