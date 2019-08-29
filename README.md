# paro
//1
// Import the required package(s) and/or class(es)
import java.util.Scanner;
import static java.lang.System.out;

//2
java.util.Calendar current =  java.util.Calendar.getInstance();
		// Create an object of Calendar class. 

		// Use getInstance() method to initialize the Calendar object.
		// Initialize the int variable year with the current year 
year = current.get(java.util.Calendar.YEAR);

//3
interface ExtraLarge{
	String extra = "This is extra-large";
	public void display();
}

class Large {
    public void Print() {
        System.out.println("This is large");
    }
}
 
class Medium extends Large {
    public void Print() {
    	  super.Print();  
        System.out.println("This is medium");
    }
}
class Small extends Medium {
    public void Print() {
        super.Print();
        System.out.println("This is small");
    }
