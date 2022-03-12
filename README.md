# Sayilari-Buyukten-Kucuge-Siralama
Patika.dev > Java101 > Koşullu İfadeler ve Kod Blokları > Pratik5 - Sayıları Büyükten Küçüğe Sıralama

## Girilen 3 sayıyı "küçükten büyüğe" sıralayan programı yazınız.

          import java.util.*;
          
          public class sayilarıSiralama {
          
              public static void main(String[] args) {
                  
                  // Yeni bir tarayıcı(scanner) oluştur.
                  Scanner sc= new Scanner(System.in);
                  
                  // Kullanıcıdan sayı değerlerini al.
                  System.out.println("Birinci sayı: ");
                  int n1 =sc.nextInt();
                  
                  System.out.println("İkinci sayı: ");
                  int n2 =sc.nextInt();
                  
                  System.out.println("Üçüncü sayı: ");
                  int n3 =sc.nextInt();
                  
                  if (num1 > num2 && num1 > num3) {
                      if (num2 > num3)
                          System.out.print(num1 + ">" + num2 + ">" + num3);
                      else
                          System.out.print(num1 + ">" + num3 + ">" + num2);
                  }
                  
                  if (num2 > num1 && num2 > num3) {
                      if (num1 > num3) 
                          System.out.print(num2 + ">" + num1 + ">" + num3);
                      else
                          System.out.print(num2 + ">" + num3 + ">" + num1);
                  }
                  if (num3 > num1 && num3 > num2) {
                      if (num1 > num2)
                          System.out.print(num3 + ">" + num1 + ">" + num2);
                      else
                          System.out.print(num3 + ">" + num2 + ">" + num1);
                  }
              }
          }
