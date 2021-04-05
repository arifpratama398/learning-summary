---
sidebar: auto
---

# C++ Programming Language

C++ merupakan bahasa pemrograman cross platform untuk membangun aplikasi dengan performa yang tinggi. C++ dikembangkan oleh Bjarne Stroustrup sebagai ekstensi bahasa C. C++ memberikan programmer kendali tingkat tinggi kedalam sistem dan memory. C++ mengalami 3 kali Major Update di 2011, 2014, dan 2017 menjadi C++11, C++14, dan C++17.

Alasan untuk menggunakan C++ adalah :

- C++ sangat popular di dunia pemrograman
- C++ telah digunakan dalam sistem operasi, aplikasi gui, dan system terdedikasi.
- C++ memiliki paradigma berorientasi objek sehingga membantu programmer untuk merancang aplikasi dengan struktur yang jelas dan code reusability.


## Code Structure

Sample code :

``` cpp
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}
```

Penjelasan :

**Baris 1:** `#include <iostream>` adalah header file dari library untuk menggunakan objek io, seperti `cout` (pada baris 5). Header files digunakan untuk menambah fungsional ke program C++ (import library)

**Baris 2:** `using namespace std` berarti menggunakan nama object dan variable dari library std.

> C++ mengabaikan spasi atau *white space*.

**Baris 4:**  `int main()` merupakan fungsi utama dari program C++ dimana fungsi itu yang selalu dijalankan dalam aplikasi C++. Perintah yang dijalankan berada di dalam `{}`.

**Baris 5:** `cout` (dibaca 'see-out') adalah objek yang digunakan bersama dengan *insertion operator* (`<<`) untuk output/print teks.

**Baris 6:** `return 0` merupakan akhir dan keluaran fungsi main(). angka 0 menunjukan program berhasil dieksekusi (baca exit-code).



## Input / Output

C ++ menggunakan abstraksi yang disebut stream untuk melakukan operasi input dan output dalam media sekuensial seperti layar, keyboard, atau file. Sebuah stream adalah entitas tempat program dapat memasukkan atau mengekstrak karakter ke / dari. Tidak perlu mengetahui detail tentang media yang terkait dengan streaming atau spesifikasi internalnya. Yang perlu kita ketahui adalah bahwa stream adalah sumber / tujuan karakter, dan bahwa karakter ini disediakan / diterima secara berurutan (yaitu, satu demi satu).

*Standard library* mendefinisikan beberapa objek aliran yang dapat digunakan untuk mengakses apa yang dianggap sebagai *standard input / output* karakter dalam sebuah program. 

| Stream | Deskripsi |
|--------|-----------|
| cin    | standard stream input |
| cout   | standard stream output |
| cerr   | standard stream error (output) |
| clog   | standard stream log (output)|

## Variabel, Type Data, Constant

- Type: `String`
- Default: `/`

## Operator

- Type: `String`
- Default: `/`