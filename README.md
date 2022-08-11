# patika.dev-Java101-Manav-Kasa-Programi
Java ile kullanıcıların manavdan almış oldukları ürünlerin kilogram değerlerine göre toplam tutarını ekrana yazdıran programı yazın.
## Code
import java.util.Scanner;
import java.io.*;
import java.util.*;

public class Giris
{
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        double armutkg = s.nextDouble()*2.14;
        double elmakg = s.nextDouble()*3.67;
        double domateskg = s.nextDouble()*1.11;
        double muzkg = s.nextDouble()*0.95;
        double patlıcankg = s.nextDouble()*5;
        double total = armutkg+elmakg+domateskg+muzkg+patlıcankg;
        System.out.println(total);
    }
}
