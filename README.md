# Roll-a-dice
I created this code just to have fun by a virtual dice by learning java.
import java.util.Random;
public class Main {
    
    public static void main(String[] args) {
        Random dice = new Random();
        int x= dice.nextInt(6) +1;    
            
        System.out.println("Wohoo, \n You have rolled a:" + x);
    }
}
output:
Wohoo,
 You have rolled a:6 
