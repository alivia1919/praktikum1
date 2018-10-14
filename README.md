LATIHAN1.cpp : Program menghitung Luas segitiga

alur algoritma

1. mendeklarasikan variable int A, T sebagai variable input dan float L sebagai variable hasil
2. menghitung luas dengan rumus L + A * T / 2.0 ,penjelasan: pembagian bilangan bulat dengan bilangan pecahan 2.0 akan menghasilkan     
   bilangan pecahan
3. mencetak hasilnya kelayar. cout << L << end1;

berikut code lengkapnya :

#include<iostream>

  int main() {
    int A, T;
    float L;

    A = 5;
    T = 7;

    L = A * T / 2.0;

    std::cout << "program menghitung luas segitiga" << std::endl;
    std::cout << "alas segitiga = " << A << std::endl;
    std::cout << "tinggi segitiga = " << T << std::endl;
    std::cout << "luas segitiga adalah = " << L << std::endl;
}

LATIHAN2.cpp : program mencari angka terbesar dari dua bilangan

alur algoritma

1. Menerima 2 buah input
2. Melakukan proses untuk menentukan variable mana yang memiliki bilangan terbesar
3. Melakukan pencetakan hasil proses

berikut kode lengkapnya :

#include<iostream>

int main() {
        int A,B;
        std::cout << "masukan nilai A: "; std::cin >> A;
        std::cout << "masukan nilai B: "; std::cin >> B;


        if (A > B) {
        std::cout << A << " lebih besar dari " << B >> std::endl;
        std::cout << B << " lebih kecil dari " << A >> std::endl;
        } else
        std::cout << B << " lebih besar dari " << A << std::endl;
        }
        
LATIHAN3.cpp : program mencari angka terbesar dari dua bilangan versi lain

alur algoritma

1. Menerima 2 buah input
2. Melakukan proses untuk menentukan variable mana yang memiliki bilangan terbesar
3. Melakukan pencetakan hasil proses

berikut kode lengkapnya :

#include<iostream>
using namespace std;

int main()
{
  int n1, n2;

  cout << "Masukkan bilangan pertama: ";
  cin >> n1;
  cout << "Masukkan bilangan kedua: ";
  cin >> n2;

  if(n1 > n2)
  {
    cout << n1 << " > " << n2;
  }

  if(n1 < n2)
  {
    cout << n1 << " < " << n2;
  }

  if(n1 == n2)
  {
    cout << n1 << " = " << n2;
  }

  return 0;
}

LATIHAN4 : program menentukan bilangan ganjil genap

alur algoritma :

1. Masukkan sebuah bilangan
2. Bagi bilangan tersebut dengan bilangan atau angka 2
3. Jika bilangan menghasilkan sisa pembagian 0 maka genap
4. Jika bilangan tidak menghasilkan sisa pembagian 0 maka ganjil

berikut kode lengkapnya :

#include <iostream>
using namespace std;

int main()
{
  int n;

  cout << "Masukkan angka: ";
  cin >> n;

  if ( n % 2 == 0)
    cout << n << " adalah angka genap";
  else
    cout << n << " adalah angka ganjil";

  return 0;
}


Maaf jika ada kesalahan karna saya masih dalam proses pembelajaran
jika ada yang salah mohon comment agar bisa saya perbaiki dan bisa menjadi pembelajaran kedepannya
sekian dan TERIMA KASIH
