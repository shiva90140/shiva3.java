# shiva3.java
import java.util.Scanner; 
class Swap   
{  
    public static void main(String a[])   
    {     
        Scanner sc = new Scanner(System.in);  
        System.out.println("Enter the value of x: ");
        int x = sc.nextInt();  
        System.out.println("Enter the value of y:");
        int y = sc.nextInt(); 
        System.out.println("before swapping numbers: "+x +" "+ y); 
        
        x = x + y;   
        y = x - y;   
        x = x - y;   
        System.out.println("After swapping: "+x +"  " + y);   
    }   
}  
