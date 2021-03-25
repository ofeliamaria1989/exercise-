# exercise- in Java

// calculeaza aria si perimetrul unui drptunghi
	  	int L1=5;
	  	int L2=8;
	  	int P = (L1+L2)*2;
	  	System.out.println(P);
	  	int A = L1*L2;
	  	System.out.println(A);
	  	
	  	
//from float to int using Math class
	  	float f = 3.14f;
	  	int a = Math.round(3.14f);
	  	System.out.println(a);
	  	
//Exercițiu eșuat
	    package primul_proiect_java;
import java.util.Scanner;


public class MainClass {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
	  Scanner scan = new Scanner(System.in);
	  
	  System.out.println("Cum te numesti ? : ");
	  
	  String x = scan.nextLine();
	  
	  System.out.println("Salut, "  + x  + "!");
	  
	  System.out.println("Perfect! Introdu ziua in care te-ai nascut : ");
	int a=scan.nextInt();
	String number = String.valueOf(a);
	for(int i = 0; i < number.length(); i++) {
	    int j = Character.digit(number.charAt(i), 10);
	    System.out.println("digit: " + j);
	    
	   
	}
     
	  
	  System.out.println("Perfect! Acum introdu luna in care te-ai nascut : ");
	  int b = scan.nextInt();
		String n = String.valueOf(b);
		for(int p = 0; p < n.length(); p++) {
		    int d = Character.digit(n.charAt(p), 10);
		    System.out.println("digit: " + d);
		}
System.out.println("Perfect! Acum introdu anul in care te-ai nascut : ");
	  int c = scan.nextInt();
		String nr = String.valueOf(c);
		for(int e = 0; p < nr.length(); e++) {
		    int g = Character.digit(nr.charAt(e), 10);
              int h = Character.digit(nr.charAt(e), 10);
              int j = Character.digit(nr.charAt(e), 10);

              System.out.println("digit: " + g);
              System.out.println("digit: " + h);
              System.out.println("digit: " + j);
