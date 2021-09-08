import java.util.*;
public class Hello {
    public static void main(String[] args) {
	Scanner z=new Scanner(System.in);
	String s;
	s=z.nextLine();
	int l=s.length();
	for(int i=0;i<l;i++){
	    int a=l-i-1;
	    for(int j=0;j<l;j++){
	        if(i==j)
	            System.out.print(s.charAt(j));
	        else if(j==a)
	            System.out.print(s.charAt(j));
	        else
	            System.out.print(" ");
	    }
	    System.out.println();
	}
	}
}
