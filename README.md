# ReverseAString
import java.util.Scanner;

public class ReverseString {


	public static void main(String[] args) {

		Scanner get=new Scanner(System.in);
		System.out.println("Enter the String");
		String input=get.nextLine();
		StringBuffer nn=new StringBuffer(input);
		StringBuffer output=nn.reverse();
		System.out.println("Tne output String is");
		System.out.println(output);
		

	}

}
