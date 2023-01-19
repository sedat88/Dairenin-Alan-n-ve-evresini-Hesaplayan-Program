# Dairenin-Alan-n-ve-evresini-Hesaplayan-Program

import java.util.Scanner;
public class Main {
    public static void main (String[]orgs) {
        //Değişkenlerin girilmesi.

        int r,a;
        double pi = 3.14 ;
        double i=360;

        Scanner islem = new Scanner(System.in);

        System.out.print("Dairenin yarıçapını giriniz : ");
        r = islem.nextInt();
        System.out.print("Dairenin a Açısını Giriniz: ");
        a = islem.nextInt();


        double alan = pi * r * r;
        double cevre = 2 * pi * r;
        double DilimAlan=(pi*(r*r)*a)/(i);


        System.out.println("Dairenin alanı :" + alan);
        System.out.println("Dairenin çevresi : " +cevre );
        System.out.println("Dairenin Dilim Alanı: " + DilimAlan);
