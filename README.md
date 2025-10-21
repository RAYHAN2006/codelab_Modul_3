# Program Java: Menghitung Luas Lingkaran

## Deskripsi
Program ini digunakan untuk menghitung **luas lingkaran** berdasarkan **jari-jari** yang dimasukkan oleh pengguna.  
Rumus yang digunakan adalah:

\[
Luas = \pi \times r^2
\]

---

## Kode Program
```java
import java.util.Scanner;

public class LuasLingkaran {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Masukkan jari-jari lingkaran: ");
        double r = input.nextDouble();

        double luas = 3.14 * r * r;

        System.out.println("Luas lingkaran = " + luas);

        input.close();
    }
}
