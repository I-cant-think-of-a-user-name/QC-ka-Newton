********COMPILE ON GDP*******
import java.util.Scanner;

public class Vday {

    public static void main(String[] args) {
        String newton = "LoveOfMyLifeVaish";
        Scanner loveforv = new Scanner(System.in);
        System.out.println("HI SUMEDHA HERE!! \n HAPPY BIRTHDAY VAISHHHHH!!!!\n GDP pe compile karke dekh bohot mehnat kiya hai");
        System.out.println("Enter anything to see your message");
        String hi  = loveforv.next();

        System.out.println("To ♡♡♡" + newton + "♡♡♡");
        System.out.println("V you are really beautiful both in and out.\n You always motivate to code and word hard. " +
                "Thanks for always being there to help me with everything. Always stay the same. ILYSM");
        System.out.println("Enter gibberish  to see a suprise, cus we gibberesians: ");
        String v = loveforv.next();

            int i, j, row = 6;
            for (i = 0; i < row; i++) {
                for (j = row - i; j > 1; j--) {
                    System.out.print(" ");
                }
                for (j = 0; j <= i; j++) {

                    System.out.print("♡ ");
                }
                System.out.println();
            }


        System.out.println("Have a great day lyyy");

    }
}
