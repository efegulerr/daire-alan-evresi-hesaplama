# daire-alan-cevresi-hesaplama
//patika.dev alan , çevre ödevi

import java.util.Scanner;
public class main {
    public static void main (String[] args){
        double pi= 3.14, r, alan, cevre;
        Scanner inp = new Scanner(System.in);
        System.out.println("Dairenin yarı çapını giriniz.");
        r = inp.nextInt();
        alan = pi* r * r;
        cevre = 2 * pi * r;
        System.out.println("Dairenin alanı:"+ alan);
        System.out.println("Dairenin çevresi:"+ cevre);
    }
}
