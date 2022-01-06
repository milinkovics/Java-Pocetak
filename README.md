import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
		//napraviti program koji trazi unos imena korisnika i ispuje njegovo ime
    
    Scanner scanner = new Scanner(System.in);
    
    System.out.println("Unesite vase ime ");
    
    String ime = scanner.next();
    
    System.out.println("Moje ime je "+ime);
		
		
	}
}
