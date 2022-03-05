Program that prints powers of 4 and 5 up to the entered number

Java döngüler ile girilen sayıya kadar olan 4 ve 5'in kuvvetlerini ekrana yazdıran programı yazıyoruz.

import java.util.Scanner;
public class Odev19 {
    public static void main(String[] args) {

        int k;

        Scanner input = new Scanner(System.in);  // Kullanıcıdan sayı al
        System.out.println("Enter a number :");
        k = input.nextInt();

        for(int i = 1; i <= k; i*=4) {

            System.out.println("Numbers to powers of 4: " + i);  // 4 ün kuvvetleri olan sayıları bastır
        }

        for(int j = 1; j <= k; j*=5) {

            System.out.println("Numbers to powers of 5: " + j);  // 5 in kuvvetleri olan sayıları bastır
        }

    }
}

