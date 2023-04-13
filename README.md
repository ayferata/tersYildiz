# tersYildiz
import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.print(" N sayısını giriniz : ");
        int n = input.nextInt();
        System.out.println(); // boşluk için
        for (int i =(n-1);i >= 1; i--){         

            for (int j = 1;j <= (n-i); j++){       
                System.out.print(" ");
            }
            for (int k = 1;k <= (2 * i) - 1; k++){   
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
