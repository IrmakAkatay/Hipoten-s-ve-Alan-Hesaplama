
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int a,b;
        double c,u,h,üÇevresi,üAlan;

        Scanner girdi=new Scanner(System.in);
        System.out.print("1. kenarı Giriniz :");
        a=girdi.nextInt();
        System.out.print("2.Kenarı Giriniz :");
        b= girdi.nextInt();

        c=Math.sqrt((a*a)+(b*b));
        System.out.println("Hipotenüs : "+c);

        u=(a+b+c)/2;
        System.out.println("Üçgenin alanı: "+u);

        üÇevresi = 2*u;
        System.out.println("Üçgenin çevresi: " +üÇevresi);
