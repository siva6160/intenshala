package inte;
import java.util.*;
public class internshala {

	public static void main(String[] args) {
		String name;
		int Age;
		String Bolodgroup;
		Scanner sc=new Scanner(System.in);
		System.out.println("enter name");
		name=sc.next();
		System.out.println("enter age");
		Age=sc.nextInt();
		System.out.println("enter bollod group");
		Bolodgroup=sc.next();
		System.out.println("----------------------------------------------------------");
		System.out.println("Name:"+name);
		System.out.println( "Age:"+Age);
		System.out.println("Blood Group :"+Bolodgroup);
		System.out.println("-----------------------------------------------------------");
		if (Age>=20){
			System.out.println("Your group is RED");
		}
		if (Age>=15 && Age<20){
			System.out.println("your group is BLUE ");
		}
		if (Age>=10 && Age<15){
			System.out.println("Your group is Yellow");
		}
		System.out.println("-----------------------------------------------------------------");
		
		
		

	}

}
