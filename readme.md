import java.util.Scanner;

public class Main {
public static void main(String[] args) {
int mat, fizik, kimya, türkce, tarih, müzik;

       // Scanner sınıfını ekledik
        Scanner input= new Scanner(System.in);

        // kullanıcıdan deger alıyoruz
        System.out.print("Matematik notunu giriniz :");
        mat = input.nextInt();

        System.out.print("Fizik notunu giriniz :");
        fizik = input.nextInt();

        System.out.print("Kimya notunu giriniz :");
        kimya = input.nextInt();

        System.out.print("Türkçe notunu giriniz :");
        türkce = input.nextInt();

        System.out.print("Tarih notunu giriniz :");
        tarih = input.nextInt();

        System.out.print("Müzik notunu giriniz :");
        müzik = input.nextInt();

        double toplam = (mat + fizik + kimya + türkce + tarih + müzik);
        double sonuc = toplam/6;

        System.out.println("Ortalamanız :" + sonuc);

        String s = sonuc > 60 ? "Sınıfı Geçti" : "Sınıfta Kaldı";
        System.out.println(s);
        }
    }
