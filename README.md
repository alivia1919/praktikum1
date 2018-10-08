LATIHAN1.cpp:Program menghitung Luas segitiga

alur algoritma

1. mendeklarasikan variable int A, T sebagai variable input dan float L sebagai variable hasil
2. menghitung luas dengan rumus L + A * T / 2.0 ,penjelasan: pembagian bilangan bulat dengan bilangan pecahan 2.0 akan menghasilkan bilangan pecahan
mencetak hasilnya kelayar. cout << L << end1;

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

LATIHAN2.cpp:
