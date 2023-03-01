# Vucut-Kitle-Endeks

        
        import java.util.Scanner;
        
        public class boyKiloendeks {
        
    public static void main(String[] args) {

        double boy, kilo;

        Scanner input = new Scanner(System.in);

        System.out.println(" Boyunuzu Metre Cinsinden Giriniz ");
        boy = input.nextDouble();

        System.out.println(" Kilonuzu Girin ");
        kilo = input.nextDouble();

        double sonuc = kilo/(boy*boy);

        System.out.println(" Vucut Kitle Endeksiniz " + sonuc );
        }
       }


