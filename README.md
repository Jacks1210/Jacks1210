import java.util.*;
public class loopExercise{
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        Random rando = new Random();
        System.out.println("Enter two numbers between 1 - 20");
        int num = input.nextInt();
        int num2 = input.nextInt();
        int val = -1;
        int val2 = -1;
        
        int tries = 0;
        while(val != num && val !=num2 && val2 != num && val2 != num2){
            val = rando.nextInt(20)+1;
            val2 = rando.nextInt(20)+1;
            
            
            tries++;
            
        }
        System.out.println( val + " " + val2 );
        System.out.print("Number of iterations " + tries);
            }
}
