[import java.util.Scanner;] untuk membaca inputan yang dimasukkan 

[public class konversiwaktu] untuk nama file ataupun program 

[public static void main(String[] args)] dimulainya ataupun awal dijalankan sebuah program 

[Scanner sc = new Scanner(System.in);] untuk menerima sebuah output/masukkan

[double Harga, Diskon, Persentase, Bayar;] untuk menyimpan harga,diskon,dan hasil perhitungan

[System.out.println(" ");] untuk menampilkan baris kosong 

[System.out.print("Masukkan harga = ");] untuk menampilkan kalimat "masukkan harga" dan untuk meminta pengguna untuk memasukkan harga "="

[Harga = sc.nextInt();] untuk menyimpan harga yang di telah di input/dimasukkan ke dalam variabel HARGA

[System.out.print("Masukkan diskon = ");] untuk menampikan kalimat "masukkan diskon" dan inputkan/ masukkan diskon dalam bentuk % 

[Diskon = sc.nextInt();] menyimpan inputan diskon ke dalam variabel DISKON 
untuk menampilakan baris kosong

[System.out.println(" ");] untuk menampilkan baris kosong 

[Persentase = Diskon / 100 * Harga;] Menghitung jumlah diskon yang didapat 

[System.out.println("Persentase Diskon = "+Persentase);] Menampilkan jumlah diskon yang di dalam kurung itu hitunagn dari diskon contoh 10/100 x 100.000 = 10.000

[Bayar = Harga - Persentase;] menghitung harga akhir setelah diskon 

[System.out.println("Jumlah yang harus di bayar = RP. "+Bayar);] Menampilkan harga yang harus di bayar contoh harga awal 100.0000 - diskon 10.000 = harga setelah dsikon 90.000

[System.out.println(" ");] untuk menampilkan baris kosong 