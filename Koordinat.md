---
Judul: Koordinat Titik, Jarak, Vektor, dan Garis.
Kelompok: 1
Nama Anggota : ["Salma Fitri Bakhitoh
25030630032", "Halimah Sa'adatur Rahmah 25030630034", "Zuhrotul Jannatil Karimah 
25030630057", "Fawwaz Dhiya'ulhaq 25030630077"]
---
https://markdownviewer.pages.dev/

<div align="center">
  <img src="" width="500">
    Gambar 1. paraboloida eliptik
  
</div>
<div style="text-align: center">

</div>

# Koordinat Titik, Jarak, Vektor, dan Garis. 
## 1. Koordinat Titik di Ruang
Untuk menentukan lokasi suatu titik pada bidang datar, diperlukan dua angka. Kita tahu bahwa setiap titik pada bidang datar dapat direpresentasikan sebagai pasangan terurut bilangan real (a, b), a adalah koordinat x dan b adalah koordinat y. Karena alasan ini, bidang datar disebut dua dimensi. Sedangkan, untuk menentukan lokasi suatu titik di ruang, diperlukan tiga angka. Kita merepresentasikan setiap titik di ruang dengan tiga bilangan real yang terurut (a, b, c). 
* Bidang (2D): Memerlukan 2 angka (x, y) untuk menentukan posisi.
* Bidang (3D): Memerlukan 3 angka (x, y, z) untuk menentukan posisi.

Komponen dasar sistem koordinat:
* Titik asal (O): Titik acuan (0, 0, 0)
* Sumbu koordinat: Tiga garis berarah (x, y, z) yang saling tegak lurus
* Aturan tangan kanan: Cara menentukan arah sumbu z positif (ibu jari menunjuk ke arah sumbu z positif saat jari tangan kanan melengkung dari x ke y)

Bidang dan Oktan:
* Tiga bidang koordinat:
 
   1. Bidang xy (di mana z = 0)
   2. Bidang yz (di mana x = 0)
   3. Bidang xz (di mana y = 0)
* Oktan: Ruang dibagi menjadi 8 oktan oleh ketiga bidang tersebut

Menentukan titik P(a, b, c):

* Mulai dari titik asal (0, 0, 0)
* Berjalan a satuan sepanjang sumbu x
* Berjalan b satuan sejajar sumbu y
* Berjalan c satuan sejajar sumbu z

Proyeksi titik

Setiap titik P(a, b, c) membentuk "kotak persegi panjang" di ruang.
* Proyeksi adalah bayangan titik pada bidang:

  1. Q(a, b, 0) → Proyeksi pada bidang xy.
  2. R(0, b, c) → Proyeksi pada bidang yz.
  3. S(a, 0, c) → Proyeksi pada bidang xz.

Contoh soal:

Misalkan posisi awal berada di titik asal (0, 0, 0). Anda bergerak sejauh 4 satuan sepanjang sumbu x positif, lalu bergerak sejauh 3 satuan ke arah bawah (sejajar sumbu z negatif). Tentukan koordinat posisi akhir Anda.

Penyelesaian:

[Titik ruang](D:\kuliah uny\tugas\geometri\kelompok 1\ titik ruang.jpg)

* Titik awal (0, 0, 0) 

* Bergerak sejauh 4 satuan sepanjang sumbu x positif (4, 0, 0)

* Bergerak sejauh 3 satuan ke arah bawah (sejajar sumbu z negarif) (4, 0, -3)

* Jadi, titik akhir berada di (4, 0, -3)


## 2. Jarak Antara Dua Titik
Jarak antara dua titik dalam ruang adalah perluasan dari jarak pada bidang. Fondasi utamanya tetap menggunakan Teorema Phytagoras, namun diterapkan pada tiga sumbu koordinat yang saling tegak lurus. Dalam geometri ruang sebuah titik tidak lagi diwakili oleh (x, y), tetapi diwakili oleh triple koordinat (x, y,z). Dengan adanya penambahan dimensi ketiga (sumbu z) memungkinkan kita merepresentasikan posisi titik dalam ruang hampa, mencakup panjang, lebar, dan tinggi.

  a. Rumus Jarak dalam Ruang
    
  1. Bidang (3D): Jika terdapat dua titik dalam ruang P1(x1, y2, z3) dan P2(x1, y2, z3), maka jarak d diantara keduanya adalah: 
d  =(x2-x1)2+(y2-y1)2+(z2-z1)2

  2. Sifat Non-negatif: Karena setiap komponen selisih koordinat dikuadratkan, hasil di bawah akar akan selalu positif atau nol, sehingga jarak tidak pernah bernilai negatif.

  b. Konsep Titik Tengah (Midpoint) dalam Ruang 

   Titik tengah M yang menghubungkan P1(x1, y2, z3)dan  P2(x1, y2, z3)adalah: M= (x1+x22, y1+y22, z1+z22 ) 
  
  c. Aplikasi Geometris: Dari Lingkaran ke Bola

   Di dalam ruang, konsep lingkaran diperluas menjadi bola. Sebuah bola didefinisikan sebagai semua titik (x, y, z) yang jaraknya dari titik pusat tertentu(h,k,l) adalah konstan (r).
   * Persamaan Bola
     
  Menggunakan rumus jarak, persamaan standar sebuah bola adalah:
  (x-h)2+(y-k)2+(z-l)2=r2

 Contoh soal:

   1. Tentukan jarak antara titik P1(1, 0, 2) dan  P2(3, 4, 6) dalam ruang koordinat tiga dimensi.
Penyelesaian:

      a. Identifikasi koordinat:

       * P1:x1=1, y1=0, z1=2 

       *  P2:x2=3, y2=4, z2=6

      b. Gunakan rumus jarak ruang:

         d  =(x2-x1)2+(y2-y1)2+(z2-z1)2

      c. Substitusikan nilai ke dalam rumus jarak:

         d  =(3-1)2+(4-0)2+(6-2)2
 
         d  =(2)2+(4)2+(4)2
   
         d  =4+16+16

         d  =36

         d  =6

         jadi, jarak antara kedua titik tersebut adalah 6 satuan.

   2. Tentukan nilai x jika jarak antara titik A(2,-1, 4) dan  B(x, 3, 4) adalah 5 satuan.

       Penyelesaian: 

      d. Identifikasi koordinat:

         * P1:x1=1, y1=0, z1=2

         * P2:x2=x, y2=4, z2=6

      e. Gunakan rumus jarak ruang:
          d =(x2-x1)2+(y2-y1)2+(z2-z1)2

      f. Substitusikan nilai ke dalam rumus jarak:

         5 =(x-2)2+(3-(-1))2+(4-4)2
         5  =(x-2)2+(4)2+(0)2
         5  =(x-2)2+16
         25 =(x-2)2+16
         9   =(x-2)2
         x-2=3              atau           x-2=-3
         x=5              atau           x=-1
         jadi, nilai yang memenuhi x adalah  antara 5 atau -1. 



## 3. Vektor dalam Ruang
  1 . Definisi Vektor dalam Ruang
      Vektor dalam ruang adalah besaran yang memiliki nilai dan arah yang terletak di dalam ruang tiga dimensi. Setiap vektor dapat dinyatakan dalam koordinat kartesius menggunakan tiga sumbu yang saling tegak lurus, yaitu sumbu x, sumbu y, dan sumbu z.

Notasi vektor:
  * Komponen:  v = (v1, v2, v3)
  * Vektor Satuan:  v =v1i+v2j+v3k
  Dimana i, j, k  adalah vektor basis pada sumbu x, y,z)

2. Operasi Dasar Vektor

  Jika diketahui a = (a1, a2, a3) dan b = (b1, b2, b3) , maka:
  * Penjumlahan dan Pengurangan
  Dilakukan dengan menjumlahkan atau mengurangkan komponen yang bersesuaian.
  a b = (a1b1,a2b2,a3b3)

  * Perkalian Skalar
  Jika k adalah sebuah skalar, maka:
   ka =(ka1, ka2, ka3)
  * Panjang Vektor
  Jarak dari titik pangkal ke titik ujung vektor:
  a =a12+a22+a32

3. Perkalian Dua Vektor
  Ada dua jenis perkalian utama dalam R3:

  * Dot Product (Perkalian Titik)

     Hasil dari perkalian titik adalah sebuah skalar. Digunakan untuk mencari sudut atau proyeksi.
    Rumus Komponen: a b =a1b1+a2b2+a3b3> Rumus Sudut: a b =a b cos 

     Sifat: a .b =a b sin  (Luas jajar genjang yang dibentuk kedua vektor).


  * Cross Product (Perkalian Silang)
    Hasil dari perkalian silang adalah sebuah vektor yang tegak lurus terhadap bidang yang dibentuk a dan b .

 
4. Aplikasi Vektor dalam Ruang

  * Vektor Posisi: Menentukan letak titik P(x,y,z) relatif terhadap titik asal O(0,0,0).
  * Proyeksi Ortogonal: Mencari bayangan satu vektor pada arah vektor lainnya.
  * Persamaan Garis dan Bidang: Digunakan dalam kalkulus peubah banyak untuk menentukan geometri ruang.

5. Contoh Soal dan Penyelesaiannya:

    Diketahui dua buah vektor a dan b  sebagai berikut:

      a =2i-j+3k

      b =i+2j-2k

   Tentukanlah:
   
      1. Hasil perkalian titik (a .b )
         
      2. Panjang masing-masing vektor a dan b
         
      3. Besar sudut yang dibentuk oleh kedua vektor

     Penyelesaian:
   
      1. a .b =(ax.bx) + (ay.by) + (az.bz)

         a .b =(2.1)+(-1.2)+(3.-2)

         a .b =2-2-6

         a .b =-6

      2. Menggunakan rumus Pythagoras ruang: v =x2+y2+z2
         * Panjang a :

           a =22+(-1)2+32

           a =4+1+9
 
           a =14

         * Panjang b :

             b =12+22+(-2)2

             b=1+4+4
 
             b =9

             b =3

      3. Menggunakan definisi perkalian titik a .b =a b cos 

            cos =a .b a b 

            cos =-614.3

            cos =-214

            cos =-214

            cos =-1714

            =arccos(-147)=122,3 derajat




## 4. Garis dalam Ruang
  a. Persamaan garis dalam ruang
  
  Untuk menentukan sebuah garis dalam ruang, kita membutuhkan dua informasi utama:
  
   * Satu titik tetap yang dilalui garis tersebut, misal P1(x1,y1,z1)

  * Vektor arah yang sejajar dengan garis tersebut, misal
    v=ai+bj+ck atau v=(a,b,c)
    
    1. Persamaan Vektor
       
       Jika r adalah posisi titik sembarang (x,y,z)pada garis, maka:
        r=r0+tv
        Di mana:
        * r0 adalah vektor posisi titik P1

        * t adalah skalar(parameter)
    2. Persamaan Parametrik

        Dengan menguraikan komponen di atas, kita mendapatkan

        x=x1+at

        y=y1+bt
  
       z=z1+c

    3. Persamaan Simetrik

       Jika kita mengeliminasi parameter t (dengan syarat a,b,c tidak samaa dengan 0), maka diperoleh
       x-x1a=y-y1b=z-z1c

b. Kedudukan dua garis dalam ruang

Dua garis dalam ruang memiliki empat kemungkinan hubungan:

  1. Berpotongan: Memiliki satu titik persekutuan

  2. Sejajar: Memiliki arah yang sama dan tidak memiliki titk persekutuan.

  3. Berimpit: Memiliki arah yang sama dan semua titiknya sama.

  4. Bersilangan: Tidak sejajar dan tidak berpotongan (berada di bidang yang berbeda)


c. Sudut Antara Dua Garis

   Sudut antara dua garis ditentukan oleh sudut antara kedua vektor arahnya (v1 dan v2):
   cos =v1 . v2v1  v2


d. Contoh Soal dan Penyelesaiaan


