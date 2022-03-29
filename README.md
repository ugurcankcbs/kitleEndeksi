import java.util.Scanner;

public class Endeks {
    public static void main (String[] args) {


        Scanner inp = new Scanner(System.in);
        double boy;
        System.out.println("Lütfen boyunuzu metre cinsinden giriniz: ");
        boy = inp.nextDouble();

        int kilo ;
        System.out.println("Lütfen kilonuzu giriniz: ");
        kilo = inp.nextInt();

        double endeks = kilo/(boy*boy);
        System.out.println("Boy/Kilo endeksiniz: " + endeks);
    }
}
