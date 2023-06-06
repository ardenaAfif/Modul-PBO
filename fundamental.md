# Fundamental Java
>> [Kembali](README.md)
# Daftar Isi
- [Tipe Data](#tipe-data)
- [Operator](#operator)
- [Input & Output](#input-dan-output)
- [Fundamental OOP](#class-object-attribute-dan-method)

## Tipe Data
>>> [UP](#fundamental-java)

> ### String

Di dalam bahasa pemrograman Java, string merupakan sebuah tipe data reference. Tipe data ini diperlakukan sebagai sebuah obyek. String adalah kumpulan beberapa karakter (char). String sendiri sebenarnya merupakan sebuah class yang terdapat dalam library Java dan digunakan untuk memanipulasi karakter. 

Berikut contoh sintaks deklarasi String :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/string.png" width="500">

Ada banyak method lain yang disediakan oleh kelas String yang bisa mempermudah kita  memanipulasi sebuah teks. Berikut adalah kumpulan beberapa method yang sering digunakan:

| No. | Nama Method                           | Deskripsi                                                                      |
|-----|---------------------------------------|--------------------------------------------------------------------------------|
| 1   | length()                              | Digunakan untuk mengetahui panjang atau jumlah karakter dalam string.          |
| 2   | charAt(int index)                     | Digunakan untuk mengambil sebuah karakter berdasarkan indeks tertentu.         |
| 3   | format(String format, Object... args) | Digunakan untuk memformat sebuah string.                                       |
| 4   | substring(int beginIndex)             | Mengembalikan/menghasilkan substring berdasarkan indeks yang diberikan.        |
| 5   | contains(CharSequence s)              | Mengembalikan/menghasilkan nilai true atau false setelah mencocokkan karakter. |
| 6   | equals(Object object)                 | Memeriksa apakah nilai objek sama dengan nilai string.                         |
| 7   | isEmpty()                             | Memeriksa apakah sebuah string itu kosong atau tidak.                          |
| 8   | concat(String s)                      | Mengkonsolidasikan sebuah string.                                              |
| 9   | replace(char a, char b)               | Mengganti suatu karakter di dalam string.                                      |
| 10  | indexOf(String a)                     | Mengetahui indeks dari sebuah substring.                                       |
| 11  | toLowerCase()                         | Mengubah format string menjadi huruf kecil semua.                              |
| 12  | toUpperCase()                         | Mengubah format string menjadi huruf kapital semua.                            |
| 13  | trim()                                | Menghapus spasi awal dan akhir dari string.                                    |
| 14  | valueOf(int value)                    | Mengkonversi tipe yang diberikan menjadi sebuah string.                        |
| 15  | compareTo()                           | Membandingkan dua nilai.                                                       |

> ### Integer
Merupakan tipe data integer 32 bit yang digunakan untuk menyimpan angka dalam range cukup besar, yakni antara -2,147,483,648 sampai 2,147,483,647 dengan nilai default 0. Jika kita tidak memperhatikan penggunaan memori, tipe data inilah yang biasanya dipakai. 

Berikut contoh sintaks Integer :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/int.png" width="500">


> ### Array
Array adalah obyek yang bisa digunakan untuk menyimpan kumpulan data lebih dari satu dengan tipe  sama. Array memiliki jumlah data yang fixed (tetap).

- ### Ilustrasi Array

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/array_ilustrasi.png" width="400">

Angka di atas menunjukkan indeks dari array tersebut, yakni dimulai dari 0 sampai 6. Setiap kolom nilai bisa disebut sebagai elemen.

Berikut contoh sintaks Array :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/array.png" width="500">

> ### Float & Double
- Float merupakan sebuah tipe data yang bisa digunakan untuk menampung angka desimal. Nilai default-nya 0.0f.

- Double merupakan sebuah tipe data yang mirip seperti tipe data float, namun memiliki kapasitas yang lebih besar. Nilai default-nya 0.0d.

Berikut contoh sintaks Float dan Double

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/float%20double.png" width="500">

> ### Boolean
Boolean merupakan sebuah tipe data yang memiliki 2 (dua) macam nilai, yaitu true dan false. Nilai default-nya false.

Berikut sintaks boolean:

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/boolean.png" width="500">


## Operator
>>> [UP](#fundamental-java)

Operator dalam Java merupakan suatu simbol yang digunakan untuk melakukan suatu operasi tertentu (memanipulasi, mengolah) satu atau lebih variabel. Variabel yang dioperasikan disebut sebagai operand. Bahasa Java memiliki banyak operator yang dapat digunakan dan bisa dikelompokkan menjadi beberapa kategori, seperti :

- [Operasi Assignment](#operasi-assignment)
- [Operasi Arithmetic](#operasi-arithmetic)
- Operasi Unary
- [Operasi Equality dan Relational](#operasi-equality-and-relational)
- Operasi Conditional

Kita akan membahas Operasi Assignment, Arithmetic, Equality dan Relational saja.

### Operasi Assignment
Operator Assignment adalah salah satu operator yang umum digunakan dalam pemrograman Java. Dalam operasi ini, sebuah nilai diberikan kepada sebuah variabel dengan menggunakan simbol operator '='. Tugas operator Assignment adalah menetapkan nilai yang ada di sebelah kanan operator kepada variabel yang ada di sebelah kiri operator.

Berikut contoh penggunaan Operator Assignment :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/assignment.png" width="400">


### Operasi Arithmetic
Java menyediakan berbagai operator aritmatika yang digunakan untuk melakukan perhitungan matematika. 

Operator-operator aritmatika yang umum digunakan di Java adalah sebagai berikut:

| Operator | Deskripsi                                  |
|----------|--------------------------------------------|
| +        | Operator penambahan                         |
| -        | Operator pengurangan                        |
| *        | Operator pengalian                          |
| /        | Operator pembagian                          |
| %        | Operator sisa hasil atau modulus            |

Berikut contoh penggunaan Operator Arithmetic :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/aritmatika.png" width="400">


### Operasi Equality dan Relational
Operator Equality and Relational digunakan untuk membandingkan dan menentukan hubungan antara dua variabel atau operand. Operator-operator ini menghasilkan nilai boolean, yaitu true (benar) atau false (salah), tergantung pada hasil perbandingan yang dilakukan.

Berikut adalah beberapa operator Equality and Relational yang tersedia dalam pemrograman Java:

| Operator | Deskripsi                 |
|----------|---------------------------|
| `==`     | Equal to                  |
| `!=`     | Not equal to              |
| `>`      | Greater than              |
| `>=`     | Greater than or equal to  |
| `<`      | Less than                 |
| `<=`     | Less than or equal to     |

Berikut contoh penggunaan Operator Operasi Equality dan Relational :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/Equality%20and%20Relational.png" width="400">

## Input dan Output
>>> [UP](#fundamental-java)

- ### Input
Pemrograman Java terdiri dari tiga komponen utama, yaitu Input, Proses, dan Output. Pada materi sebelumnya, kita telah mempelajari beberapa kode yang terkait dengan proses dan output. Pada materi ini, kita akan mempelajari bagaimana cara mengambil input, melakukan proses terhadap input tersebut, dan menampilkan hasilnya pada layar.

Scanner merupakan kelas yang menyediakan fungsi-fungsi untuk membaca dan mengambil input dari pengguna. Scanner memiliki kemudahan yang dapat membaca teks, baik yang memiliki tipe data primitif maupun string.

Contoh penggunaan _Scanner_ :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/scanner.png" width="400">

NB.
- Jangan lupa untuk import `import java.util.Scanner;`
- dan deklarasikan scanner `Scanner scanner = new Scanner(System.in);`

- ### Output (_print dan println_)
Tentunya kita sudah familiar bagaimana memberikan output dari yang sudah kita praktikkan pada beberapa contoh program sebelumnya. Pada dasarnya kedua fungsi di atas sama-sama memiliki peran untuk menampilkan teks di Console maupun dari IDE yang kita gunakan.

Apa yang berbeda diantara 2 fungsi di atas? Berikut implementasinya:

1. Penggunaan `println` akan menampilkan teks dan tambahan baris baru.

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/print.png" width="400">

2. Sedangkan fungsi print menampilkan keluaran berupa teks sesuai dengan yang dimasukkan.

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/println.png" width="400">

## Class, Object, Attribute dan Method
>>> [UP](#fundamental-java)

Berikut materi tentang fundamental Pemrograman Berorientasi Objek

- ### Class
Class adalah blueprint dari objek yang dibentuk, dimana dapat menggambarkan ciri-ciri objek secara umum.

Contoh sintaks dari _class_ :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/class.png" width="400">


- ### Object

Objek adalah hasil instansiasi/bentukan dari sebuah class. Dengan kata lain satu class dapat membentuk objek sampai tak terhingga.

Contoh sintaks dari _Object_ :

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/object.png" width="500">

- ### Attribute

Atribut merupakan ciri yang ada pada suatu objek.

Contoh sintaks dari _Attribute_ : 

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/attribute.png" width="400">

- ### Method
Method merupakan fungsi yang digunakan untuk memanipulasi atau mengakses nilai pada atribut. Method berisi sekumpulan kode program yang dapat diakses sewaktu-waktu hanya dengan pemanggilan nama method tersebut. 

Contoh sintaks dari _Method_ : 

<img src="https://github.com/ardenaAfif/Modul-PBO/blob/main/assets/method.png" width="400">
