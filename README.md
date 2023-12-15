import java.util.Scanner;

public class test {
    public static void main(String[] args) {
        int heat;

        Scanner input = new Scanner(System.in);
        System.out.println("Sıcaklık Giriniz:");
        heat = input.nextInt();

        if (heat < 5) {
            System.out.println("Kayak Yapabilirsiniz.");
        } else if (heat >= 5 && heat <= 25) {
            if (heat <= 15)
                System.out.println("sinemaya gidilebilir.");
        }
        if (heat >= 10)
            System.out.println("pikniğe gidilebilir.");
        else {
            System.out.println("Yüzme için uygundur.");
        }

    }
}
