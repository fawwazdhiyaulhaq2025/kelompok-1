---
Judul: Koordinat Titik, Jarak, Vektor, dan Garis.
Kelompok: 1
Nama Anggota : ["Salma Fitri Bakhitoh
25030630032", "Halimah Sa'adatur Rahmah 25030630034", "Zuhrotul Jannatil Karimah 
25030630057", "Fawwaz Dhiya'ulhaq 25030630077"]
---

# Koordinat Titik, Jarak, Vektor, dan Garis. 
# Bab 1 Sistem Koordinat dalam Ruang 3D
## 1.1 Sistem Koordinat Kartesius 3D
Sistem koordinat Kartesius tiga dimensi (3D) terdiri dari tiga sumbu yang saling tegak lurus satu sama lain, yang berpotongan di sebuah titik yang disebut titik asal atau origin, dilambangkan dengan huruf $O$. Ketiga sumbu tersebut adalah sumbu-$X$, sumbu-$Y$, dan sumbu-$Z$, di mana:
- Sumbu-$X$ biasanya digambar mengarah ke depan-kanan pembaca (keluar dari bidang gambar).
- Sumbu-$Y$ digambar mengarah ke kanan (ke samping).
- Sumbu-$Z$ digambar mengarah ke atas.

![alt text](blob:https://markdownviewer.pages.dev/23968116-6142-45ee-b12d-2330f1eb62eb)

Arah positif dari ketiga sumbu mengikuti kaidah tangan kanan (right-hand rule). Jika ibu jari, telunjuk, dan jari tengah tangan kanan diluruskan sehingga ketiganya saling tegak lurus, maka ibu jari menunjuk arah positif sumbu-$Z$, telunjuk menunjuk arah positif sumbu-$Y$, dan jari tengah menunjuk arah positif sumbu-$X$. Sistem yang demikian disebut sistem koordinat tangan kanan dan merupakan konvensi standar dalam matematika dan fisika.

Komponen dasar sistem koordinat:
- Titik asal $(O)$: Titik acuan $(0, 0, 0)$.
- Sumbu koordinat: Tiga garis berarah $(x, y, z)$ yang saling tegak lurus.
- Aturan tangan kanan: Cara menentukan sumbu $z$ positif (seperti gambar di atas). 

Ketiga sumbu koordinat ini menentukan tiga bidang koordinat yang saling tegak lurus, yaitu:
- Bidang $XY$: bidang yang memuat sumbu-$X$ dan sumbu-$Y$; persamaannya adalah $z = 0$.
- Bidang $YZ$: bidang yang memuat sumbu-$Y$ dan sumbu-$Z$; persamaannya adalah $x = 0$.
- Bidang $XZ$: bidang yang memuat sumbu-$X$ dan sumbu-$Z$; persamaannya adalah $y = 0$.

![alt text](blob:https://markdownviewer.pages.dev/6c14bf07-722b-4fc4-bda8-386078a1914a)

Setiap titik $P$ di ruang tiga dimensi dapat dinyatakan secara unik dengan tripel terurut $(x, y, z)$ di mana:
- $x$ adalah jarak berarah dari titik $P$ ke bidang $YZ$, diukur sejajar dengan sumbu-$X$ (disebut absis).
- $y$ adalah jarak berarah dari titik $P$ ke bidang $XZ$, diukur sejajar dengan sumbu-$Y$ (disebut ordinat).
- $z$ adalah jarak berarah dari titik $P$ ke bidang $XY$, diukur sejajar dengan sumbu-$Z$ (disebut aplikat).

Tripel $(x, y, z)$ disebut koordinat Kartesius dari titik $P$, dan dituliskan sebagai $P(x, y, z)$. Penting untuk dipahami bahwa nilai $x$, $y$, dan $z$ dapat berupa bilangan positif, negatif, maupun nol, tergantung pada posisi titik tersebut terhadap titik asal dan bidang-bidang koordinat.


> CONTOH SOAL:
> 1. Tentukan koordinat titik-titik berikut dalam ruang tiga dimensi:
a) Titik $A$ yang berjarak $3$ satuan dari bidang $YZ$, $4$ satuan dari bidang $XZ$, dan $5$ satuan dari bidang $XY$, semuanya pada arah positif.
b) Titik $B$ di bidang $XY$ yang berjarak $2$ satuan dari sumbu-$X$ (pada arah positif sumbu-$Y$) dan $7$ satuan dari sumbu-$Y$ (pada arah negatif sumbu-$X$).
Jawab:
a) Jarak $3$ satuan dari bidang $YZ$ pada arah positif berarti $x = 3$.
    Jarak $4$ satuan dari bidang $XZ$ pada arah positif berarti $y = 4$.
    Jarak $5$ satuan dari bidang $XY$ pada arah positif berarti $z = 5$.
    Jadi, $A = (3, 4, 5)$.
b) Titik $B$ di bidang $XY$ berarti $z = 0$.
    Berjarak $7$ satuan dari sumbu-$Y$ pada arah negatif sumbu-$X$ berarti $x = −7$.
    Berjarak $2$ satuan dari sumbu-$X$ pada arah positif sumbu-$Y$ berarti $y = 2$.
    Jadi, $B = (−7, 2, 0)$.

## Oktan dalam Ruang 3D
Tiga bidang koordinat $(XY, YZ, dan XZ)$ membagi ruang tiga dimensi menjadi delapan bagian yang disebut oktan (octant). Pembagian ini analog dengan pembagian bidang dua dimensi menjadi empat kuadran oleh sumbu-$X$ dan sumbu-$Y$. Setiap oktan ditentukan oleh kombinasi tanda dari koordinat $x$, $y$, dan $z$ dari titik-titik yang berada di dalamnya.

Kedelapan oktan tersebut adalah sebagai berikut:
| Nama Oktan | Tanda Kiri-Kanan | Kondisi Nilai Koordinat |
| :--- | :---: | :--- |
| **Oktan I** | $(+, +, +)$ | $x > 0, y > 0, z > 0$ |
| **Oktan II** | $(-, +, +)$ | $x < 0, y > 0, z > 0$ |
| **Oktan III** | $(-, -, +)$ | $x < 0, y < 0, z > 0$ |
| **Oktan IV** | $(+, -, +)$ | $x > 0, y < 0, z > 0$ |
| **Oktan V** | $(+, +, -)$ | $x > 0, y > 0, z < 0$ |
| **Oktan VI** | $(-, +, -)$ | $x < 0, y > 0, z < 0$ |
| **Oktan VII** | $(-, -, -)$ | $x < 0, y < 0, z < 0$ |
| **Oktan VIII**| $(+, -, -)$ | $x > 0, y < 0, z < 0$ |

![alt text](blob:https://markdownviewer.pages.dev/ab2c14d3-241c-4b25-b2f9-043f70223305)

Oktan pertama (oktan I) adalah oktan di mana ketiga koordinat bernilai positif, dan biasanya menjadi oktan yang paling sering dijadikan acuan dalam ilustrasi gambar. Konvensi penomoran oktan dapat bervariasi antar penulis, sehingga ada beberapa buku yang menggunakan penomoran berbeda. Yang penting untuk dipahami adalah konsep pembagian ruang oleh tiga bidang koordinat tersebut.

> CONTOH SOAL:
> 1. Tentukan di oktan manakah masing-masing titik berikut berada:
a) $P(2, −3, 5)$&emsp;&emsp;b) $Q(−1, −4, −6)$&emsp;&emsp;c) $R(3, 2, −3)$&emsp;&emsp;d) $S(−5, 4, 1)$
Jawab:
a) $P(2, −3, 5)$ memiliki tanda $(+, −, +)$ → Oktan IV.
b) $Q(−1, −4, −6)$ memiliki tanda $(−, −, −)$ → Oktan VII.
c) $R(3, 2, −3)$ memiliki tanda $(+, +, −)$ → Oktan V.
d) $S(−5, 4, 1)$ memiliki tanda $(−, +, +)$ → Oktan II.
![alt text](blob:https://markdownviewer.pages.dev/39e0282b-a293-4c2c-8087-a74d078acbc5)

## 1.2 Penggambaran dan Lokasi Titik dalam Ruang
Untuk menggambar titik $P(x, y, z)$ dalam ruang tiga dimensi pada kertas (yang sebenarnya hanya dua dimensi), kita menggunakan teknik proyeksi yang disebut proyeksi paralel. Sumbu-$X$ biasanya digambar miring ke bawah-kiri dengan sudut sekitar $30°$ terhadap horizontal, sumbu-$Y$ digambar horizontal ke kanan, dan sumbu-$Z$ digambar vertikal ke atas. Skala pada sumbu-$X$ biasanya diperpendek sekitar setengah dari skala asli untuk memberikan ilusi perspektif tiga dimensi.
Langkah-langkah untuk menggambar titik $P(a, b, c):$
1. Mulailah dari titik asal $O$.
2. Bergerak sejauh a satuan sepanjang sumbu-$X$ (positif jika $a > 0$, negatif jika $a < 0$), tiba di titik $P₁(a, 0, 0)$.
3. Dari $P₁$, bergerak sejauh $b$ satuan sejajar sumbu-$Y$, tiba di titik $P₂(a, b, 0)$. Titik $P₂$ adalah proyeksi titik $P$ pada bidang $XY$.
4. Dari $P₂$, bergerak sejauh $c$ satuan sejajar sumbu-$Z$, sampai di titik $P(a, b, c)$.

![alt text](blob:https://markdownviewer.pages.dev/3e30c144-3b5b-4706-8386-eaf46f14150f)
Cara lain untuk menggambarkan posisi titik $P(a, b, c)$ adalah dengan membayangkan sebuah balok (parallelepiped persegi panjang) yang salah satu sudutnya berada di titik asal $O$ dengan tiga sisi terletak sepanjang ketiga sumbu koordinat. Panjang sisi balok pada sumbu-$X$ adalah $|a|$, pada sumbu-$Y$ adalah $|b|$, dan pada sumbu-$Z$ adalah $|c|$. Titik $P$ berada pada sudut balok yang berseberangan diagonal dengan titik $O$.

> CONTOH SOAL:
> 1. Misalkan posisi awal berada di titik asal $(0, 0, 0)$. Anda bergerak sejauh $4$ satuan sepanjang sumbu $x$ positif, lalu bergerak sejauh $3$ satuan ke arah bawah (sejajar sumbu $z$ negatif). Tentukan koordinat posisi akhir Anda.
Jawab:
-- Titik awal $(0, 0, 0)$
-- Bergerak sejauh $4$ satuan sepanjang sumbu $x$ positif $(4, 0, 0)$
-- Bergerak sejauh $3$ satuan ke arah bawah (sejajar sumbu $z$ negatif) $(4, 0, −3)$
-- Jadi, titik akhir berada di $(4, 0, −3)$
![alt text](blob:https://markdownviewer.pages.dev/c20ef9fa-ca86-4614-954b-c97a2204d883)

## 1.3 Proyeksi Titik pada Sumbu dan Bidang Koordinat
Proyeksi merupakan konsep penting dalam geometri analitik tiga dimensi. Proyeksi sebuah titik $P(x, y, z)$ pada suatu objek lain (sumbu atau bidang) adalah titik terdekat pada objek tersebut dari titik $P$. Karena objek-objek koordinat yang kita pertimbangkan (sumbu dan bidang) saling tegak lurus, maka proyeksi-proyeksinya dapat ditentukan dengan sangat mudah.
1. Proyeksi pada sumbu koordinat
Proyeksi titik $P(x, y, z)$ pada masing-masing sumbu koordinat adalah:
• Proyeksi $P$ pada sumbu-$X = (x, 0, 0)$
• Proyeksi $P$ pada sumbu-$Y = (0, y, 0)$
• Proyeksi $P$ pada sumbu-$Z = (0, 0, z)$
Proyeksi pada suatu sumbu diperoleh dengan mempertahankan koordinat yang sesuai dengan sumbu tersebut, dan mengenolkan dua koordinat lainnya.

2. Proyeksi pada bidang koordinat
Proyeksi titik $P(x, y, z)$ pada masing-masing bidang koordinat adalah:
• Proyeksi $P$ pada bidang $XY = (x, y, 0)$
• Proyeksi $P$ pada bidang $YZ = (0, y, z)$
• Proyeksi $P$ pada bidang $XZ = (x, 0, z)$
Proyeksi pada suatu bidang diperoleh dengan mempertahankan dua koordinat yang sesuai dengan bidang tersebut, dan mengenolkan satu koordinat yang tegak lurus dengan bidang itu.

> CONTOH SOAL:
> 1. Diketahui titik $A(−2, 5, 7)$. Tentukan:
a) Koordinat proyeksi $A$ pada sumbu$-$X, sumbu-$Y$, dan sumbu-$Z$.
b) Koordinat proyeksi $A$ pada bidang $XY$, $YZ$, dan $XZ$.
c) Koordinat refleksi (cermin) $A$ terhadap bidang $XY$.
Jawab:
a) Proyeksi $A$ pada sumbu-$X = (−2, 0, 0)$.
&emsp;Proyeksi $A$ pada sumbu-$Y = (0, 5, 0)$.
&emsp;Proyeksi $A$ pada sumbu-$Z = (0, 0, 7)$.
b) Proyeksi $A$ pada bidang $XY = (−2, 5, 0)$.
&emsp;Proyeksi $A$ pada bidang $YZ = (0, 5, 7)$.
&emsp;Proyeksi $A$ pada bidang $XZ = (−2, 0, 7)$.
c) Refleksi $A$ terhadap bidang $XY$ diperoleh dengan membalik tanda koordinat $z: (−2, 5, −7)$.

## Sistem Koordinat Silinder
Selain sistem koordinat Kartesius, terdapat sistem koordinat lain yang sering digunakan dalam ruang tiga dimensi, yaitu sistem koordinat silinder. Sistem ini sangat berguna untuk menggambarkan objek-objek yang memiliki simetri putar terhadap suatu sumbu, seperti silinder, kerucut, dan permukaan rotasi lainnya.

Dalam sistem koordinat silinder, sebuah titik $P$ di ruang dinyatakan dengan tripel terurut $(r, θ, z)$, di mana:
- $r$ adalah jarak titik $P$ dari sumbu-$Z$ (selalu bernilai non-negatif, $r ≥ 0)$.
- $θ$ adalah sudut yang dibentuk oleh proyeksi $OP$ pada bidang $XY$ dengan sumbu-$X$ positif (sudut polar), diukur berlawanan arah jarum jam dari sumbu-$X$ positif. Biasanya $0 ≤ θ < 2π$.
- $z$ adalah koordinat Kartesius biasa, yaitu jarak berarah dari titik $P$ ke bidang $XY$.

Hubungan antara koordinat Kartesius $(x, y, z)$ dan koordinat silinder $(r, θ, z)$ diberikan oleh rumus berikut:
$x = r$ $cos$ $θ$,   $y = r$ $sin$ $θ$,   $z = z$

Sebaliknya, untuk mengubah dari koordinat Kartesius ke koordinat silinder, digunakan rumus:
$r = \sqrt{(x² + y²)}$,   $tan$ $θ$ $= \frac{y}{x}$,   $z = z$

Perhatikan bahwa dalam menentukan $θ$ dari $tan$ $θ$ $= \frac{y}{x}$, kita harus memperhatikan kuadran di mana titik proyeksi $(x, y)$ berada untuk mendapatkan nilai $θ$ yang benar (yaitu $0 ≤ θ < 2π$).

> CONTOH SOAL:
> 1. Ubahlah titik $P(2, 2\sqrt{3}, 5)$ dari koordinat Kartesius ke koordinat silinder.
Jawab:
Diketahui
-> $x = 2$ 
-> $y = 2\sqrt{3}$
-> $z = 5$
$r = \sqrt{(x² + y²)}$ = $\sqrt{(4 + 12)}$ = $\sqrt{16} = 4$.
$tan$ $θ$ $= \frac{y}{x} = \frac{2\sqrt{3}}{2} = \sqrt{3}$.
Karena $x > 0$ dan $y > 0$, titik proyeksi berada di kuadran I, sehingga $θ$ $= \frac{π}{3} = (60°)$.
$z = 5$.
Jadi, koordinat silinder titik $P$ adalah $(4, \frac{π}{3}, 5)$.


## 1.4 Sistem Koordinat Bola
Sistem koordinat bola atau koordinat sferis adalah sistem koordinat yang sangat berguna untuk menggambarkan objek-objek dengan simetri bola, seperti permukaan bola, bola berlubang, dan objek-objek lain yang berpusat di titik asal. Dalam sistem ini, sebuah titik $P$ di ruang dinyatakan dengan tripel $(ρ, θ, φ)$, di mana:
- $ρ$ (rho) adalah jarak titik $P$ dari titik asal $O$, dengan $ρ ≥ 0$.
- $θ$ adalah sudut polar (sama dengan $θ$ pada koordinat silinder), yaitu sudut yang dibentuk oleh proyeksi $OP$ pada bidang $XY$ dengan sumbu-$X$ positif. Biasanya $0 ≤ θ < 2π$.
- $φ$ (phi) adalah sudut yang dibentuk oleh ruas garis $OP$ dengan sumbu-$Z$ positif (sudut polar atas / sudut kolatitude). Biasanya $0 ≤ φ ≤ π$.

Beberapa buku menggunakan notasi yang berbeda untuk koordinat bola. Misalnya, dalam beberapa referensi (terutama yang berorientasi fisika), urutan dan nama variabel dapat berbeda. Konvensi yang umum di matematika adalah $(ρ, θ, φ)$ dengan $θ$ sebagai sudut azimut dan $φ$ sebagai sudut polar. Dalam ringkasan ini, kita akan menggunakan konvensi tersebut.
Hubungan antara koordinat Kartesius $(x, y, z)$ dan koordinat bola $(ρ, θ, φ)$ diberikan oleh:
- $x$ $= ρ$ $sin$ $φ$ $cos$ $θ$
- $y$ $= ρ$ $sin$ $φ$ $sin$ $θ$
- $z$ $= ρ$ $cos$ $φ$

Sebaliknya, untuk mengubah dari koordinat Kartesius ke koordinat bola:
$$ρ = \sqrt{(x² + y² + z²)}$$
$$cos φ = \frac{z}{ρ}$$   
$$tan θ = \frac{y}{x}$$
Dapat juga ditulis: $φ = arccos \frac{z}{ρ}$ dengan $0 ≤ φ ≤ π$.

> CONTOH SOAL:
> 1. Ubahlah titik $P(1, \sqrt{3}, 2)$ dari koordinat Kartesius ke koordinat bola.
Jawab:
Diketahui 
> $x = 1$, $y = \sqrt{3}$, $z = 2$.
$ρ = \sqrt{(x² + y² + z²)}$ $= \sqrt{(1 + 3 + 4)}$ $= \sqrt{8}$ $= 2\sqrt{2}$.
$cos$ $φ$ $= \frac{z}{ρ}$ $= \frac{2}{2\sqrt{2}}$ $= \frac{1}{\sqrt{2}}$ $= \frac{\sqrt{2}}{2}$, jadi $φ = \frac{π}{4}$.
$tan$ $θ$ $= \frac{y}{x}$ $= \frac{\sqrt{3}}{1}$ $= \sqrt{3}$.
Karena $x > 0$ dan $y > 0$, maka $θ$ berada di kuadran I sehingga $θ = 
\frac{π}{3}$.
Jadi, koordinat bola titik $P$ adalah $(2\sqrt{2}, \frac{π}{3}, \frac{π}{4})$.


## 1.5 Transformasi Antar Sistem Koordinat
Transformasi antar sistem koordinat sangat penting karena setiap masalah memiliki sistem koordinat yang paling sesuai. Misalnya, untuk menggambarkan permukaan bola, sistem koordinat bola jauh lebih sederhana daripada sistem Kartesius. Sementara itu, untuk masalah yang melibatkan benda berbentuk silinder, koordinat silinder lebih sesuai.
Berikut ringkasan transformasi antar tiga sistem koordinat utama:
1. Kartesisu $\leftrightarrow$ Silinder
Silinder $→$ Kartesius: $x$ $=$ $r$ $cos$ $θ$, $y$ $= r$ $sin$ $θ$, $z = z$
Kartesius $→$ Silinder: $r =$ $\sqrt{(x² + y²)}$, $θ =$ $arctan\frac{y}{x}$, $z = z$
2. Kartesius $\leftrightarrow$ Bola
Bola $→$ Kartesius: $x$ $= ρ$ $sin$ $φ$ $cos$ $θ$, $y$ $= ρ$ $sin$ $φ$ $sin$ $θ$, $z =$ $ρ$ $cos$ $φ$
Kartesius $→$ Bola: $ρ =$ $\sqrt{(x² + y² + z²)}$, $θ$ $= arctan$$\frac{y}{x}$, $φ$ $= arccos$$\frac{z}{ρ}$
3. Silinder $\leftrightarrow$ Bola 
Bola $→$ Silinder: $r =$ $ρ$ $sin$ $φ$, $θ = θ$, $z =$ $ρ$ $cos$ $φ$
Silinder $→$ Bola: $ρ =$ $\sqrt{r² + z²}$, $θ$ $= θ$, $φ$ $=$ $arcta$$\frac{r}{z}$

> CONTOH SOAL:
> 1. Sebuah titik dinyatakan dalam koordinat silinder sebagai $(3, \frac{π}{4}, 4)$. Tentukan koordinat titik tersebut dalam:
a) Sistem Kartesius&emsp;&emsp;b) Sistem bola
Jawab:
a) $r = 3$, $θ = \frac{π}{4}$, $z = 4$.
&emsp;$x =$ $r$ $cos$ $θ$ $=$ $3$ $cos$$\frac{π}{4}$ $=$ $3$ $×$ $\frac{\sqrt{2}}{2}$ $=$ $\frac{3\sqrt{2}}{2}$.
&emsp;$y$ $=$ $r$ $sin$ $θ$ $= 3$ $sin$$\frac{π}{4}$ $=$ $3$ $×$ $\frac{\sqrt{2}}{2}$ $=$ $\frac{3\sqrt{2}}{2}$.
&emsp;$z = 4$.
&emsp;&emsp;&emsp;Koordinat Kartesius: $(\frac{3\sqrt{2}}{2}, \frac{3\sqrt{2}}{2}, 4)$.
b) $ρ =$ $\sqrt{(r² + z²)}$ $= \sqrt{(9 + 16)}$ $=$ $\sqrt{25}$ $=$ $5$.
&emsp;$θ =$ $\frac{π}{4}$ (sama dengan silinder).
&emsp;$tan$ $φ$ $=$ $\frac{r}{z}$ $= \frac{3}{4}$, sehingga $φ$ $=$ $arctan$$\frac{3}{4}$ $≈$ $36,87°$ $≈$ $0,6435$ radian.
&emsp;&emsp;&emsp;Koordinat bola: $(5, \frac{π}{4}, arctan \frac{3}{4})$.

<div align="center">
  <img src="https://i.pinimg.com/736x/f3/06/89/f3068984ab873ffb897eebba5cbf399e.jpg" width="500">
   
</div>


## 2. Jarak Antara Dua Titik
Jarak antara dua titik dalam ruang adalah perluasan dari jarak pada bidang. Fondasi utamanya tetap menggunakan Teorema Phytagoras, namun diterapkan pada tiga sumbu koordinat yang saling tegak lurus. Dalam geometri ruang sebuah titik tidak lagi diwakili oleh $(x, y)$, tetapi diwakili oleh triple koordinat $(x, y,z)$. Dengan adanya penambahan dimensi ketiga (sumbu $z$) memungkinkan kita merepresentasikan posisi titik dalam ruang hampa, mencakup panjang, lebar, dan tinggi.

  a. Rumus Jarak dalam Ruang
    
  1. Bidang (3D): Jika terdapat dua titik dalam ruang $P_1(x_1, y_2, z_3)$ dan $P_2(x_1, y_2, z_3)$, maka jarak d diantara keduanya adalah: 
$d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}$

  2. Sifat Non-negatif: Karena setiap komponen selisih koordinat dikuadratkan, hasil di bawah akar akan selalu positif atau nol, sehingga jarak tidak pernah bernilai negatif.

  b. Konsep Titik Tengah (Midpoint) dalam Ruang 

   Titik tengah $M$ yang menghubungkan $P_1(x_1, y_2, z_3)$ dan  $P_2(x_1, y_2, z_3)$ adalah 
   $M= (\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}, \frac{z_1+z_2}{2})$
  
  c. Aplikasi Geometris: Dari Lingkaran ke Bola

   Di dalam ruang, konsep lingkaran diperluas menjadi bola. Sebuah bola didefinisikan sebagai semua titik $(x, y, z)$ yang jaraknya dari titik pusat tertentu $(h,k,l)$ adalah konstan $(r)$.
   * Persamaan Bola
     
  Menggunakan rumus jarak, persamaan standar sebuah bola adalah:
  $(x-h)^2+(y-k)^2+(z-l)^2=r^2$

 Contoh soal:

   1. Tentukan jarak antara titik $P_1(1, 0, 2)$ dan  $P_2(3, 4, 6)$ dalam ruang koordinat tiga dimensi.
Penyelesaian:

      a. Identifikasi koordinat:

       * $P_1: x_1=1, y_1=0, z_1=2$

       * $P_2: x_2=3, y_2=4, z_2=6$

      b. Gunakan rumus jarak ruang:

         $d=\sqrt{(x^2-x^1)^2+(y_2-y_1)^2+(z_2-z_1)^2}$

      c. Substitusikan nilai ke dalam rumus jarak:

         $\sqrt{d  =(3-1)^2+(4-0)^2+(6-2)^2}$
 
         $\sqrt{d  =(2)^2+(4)^2+(4)^2}$
   
         $\sqrt{d  =4+16+16}$

         $\sqrt{d  =36}$

         $d  =6$

         jadi, jarak antara kedua titik tersebut adalah 6 satuan.

   2. Tentukan nilai $x$ jika jarak antara titik $A(2,-1, 4)$ dan  $B(x, 3, 4)$ adalah 5 satuan.

       Penyelesaian: 

      d. Identifikasi koordinat:

         * $P_1:x_1=1, y_1=0, z_1=2$

         * $P_2:x_2=x, y_2=4, z_2=6$

      e. Gunakan rumus jarak ruang:
          $d =\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}$

      f. Substitusikan nilai ke dalam rumus jarak:

         $5 =\sqrt{(x-2)^2+(3-(-1))^2+(4-4)^2}$
         $5  =\sqrt{(x-2)^2+(4)^2+(0)^2}$
         $5  =\sqrt{(x-2)^2+16}$
         $25 =(x-2)^2+16$
         $9   =(x-2)^2$
         $x-2=3$    atau    $x-2=-3$
         $x=5$      atau    $x=-1$
         jadi, nilai yang memenuhi $x adalah  antara 5 atau -1. 



## 3. Vektor dalam Ruang
  1 . Definisi Vektor dalam Ruang
      Vektor dalam ruang adalah besaran yang memiliki nilai dan arah yang terletak di dalam ruang tiga dimensi. Setiap vektor dapat dinyatakan dalam koordinat kartesius menggunakan tiga sumbu yang saling tegak lurus, yaitu sumbu $x$, sumbu $y$, dan sumbu $z$.

Notasi vektor:
  * Komponen:  $\overrightarrow{v} = (v_1, v_2, v_3)$
  * Vektor Satuan:  $\overrightarrow{v} =v_1\overrightarrow{i}+v_2\overrightarrow{j}+v_3\overrightarrow{k}$
  Dimana $\overrightarrow{i}$, $\overrightarrow{j}$, $\overrightarrow{k}$ adalah vektor basis pada sumbu $x$, $y$, $z$)

2. Operasi Dasar Vektor

  Jika diketahui $\overrightarrow{a} = (a_1, a_2, a_3)$ dan $\overrightarrow{b} = (b_1, b_2, b_3)$ , maka:
  * Penjumlahan dan Pengurangan
  Dilakukan dengan menjumlahkan atau mengurangkan komponen yang bersesuaian.
  $\overrightarrow{a} \pm \overrightarrow{b} = (a_1 \pm b_1,a_2 \pm b_2, a_3 \pm b_3)$

  * Perkalian Skalar
  Jika $k$ adalah sebuah skalar, maka:
   $k\overrightarrow{a} =(ka_1, ka_2, ka_3)$
  * Panjang Vektor
  Jarak dari titik pangkal ke titik ujung vektor:
  $|\overrightarrow{a}| =\sqrt{a_1^2+a_2^2+a_3^2}$

3. Perkalian Dua Vektor
  Ada dua jenis perkalian utama dalam $R^3$:

  * Dot Product (Perkalian Titik)

     Hasil dari perkalian titik adalah sebuah skalar. Digunakan untuk mencari sudut atau proyeksi.
    Rumus Komponen: $\overrightarrow{a}\overrightarrow{b} =a_1 b_1+a_2 b_2+a_3 b_3$
    Rumus Sudut: $\overrightarrow{a} \overrightarrow{b} =|\overrightarrow{a}| |\overrightarrow{b}| cos \theta$

     Sifat: $\overrightarrow{a} \overrightarrow{b} =|\overrightarrow{a}| |\overrightarrow{b}| sin \theta$  (Luas jajar genjang yang dibentuk kedua vektor).


  * Cross Product (Perkalian Silang)
    Hasil dari perkalian silang adalah sebuah vektor yang tegak lurus terhadap bidang yang dibentuk $\overrightarrow{a}$ dan $\overrightarrow{b}=$
    



 
4. Aplikasi Vektor dalam Ruang

  * Vektor Posisi: Menentukan letak titik $P(x,y,z)$ relatif terhadap titik asal $O(0,0,0)$.
  * Proyeksi Ortogonal: Mencari bayangan satu vektor pada arah vektor lainnya.
  * Persamaan Garis dan Bidang: Digunakan dalam kalkulus peubah banyak untuk menentukan geometri ruang.

5. Contoh Soal dan Penyelesaiannya:

    Diketahui dua buah vektor a dan b  sebagai berikut:

      $\overrightarrow{a} =2\overrightarrow{i}-\overrightarrow{j}+3\overrightarrow{k}$

      $\overrightarrow{b} =\overrightarrow{i}+2\overrightarrow{j}-2\overrightarrow{k}$

   Tentukanlah:
   
      1. Hasil perkalian titik $(a .b )$
         
      2. Panjang masing-masing vektor $\overrightarrow{a}$ dan $\overrightarrow{b}$
         
      3. Besar sudut yang dibentuk oleh kedua vektor

     Penyelesaian:
   
      1. $\overrightarrow{a}.\overrightarrow{b} =(a_x.b_x) + (a_y.b_y) + (a_z.b_z)$

         $\overrightarrow{a}.\overrightarrow{b} =(2.1)+(-1.2)+(3.-2)$

         $\overrightarrow{a}.\overrightarrow{b} =2-2-6$

         $\overrightarrow{a}.\overrightarrow{b} =-6$

      2. Menggunakan rumus Pythagoras ruang: v =x2+y2+z2
         * Panjang $\overrightarrow{a}$ :

           $|\overrightarrow{a}| =\sqrt{2^2+(-1)^2+3^2}$

           $|\overrightarrow{a}| =\sqrt{4+1+9}$
 
           $|\overrightarrow{a}| =\sqrt{14}$

         * Panjang $overrightarrow{b}$ :

             $|\overrightarrow{b}| =\sqrt{1^2+2^2+(-2)^2}$

             $|\overrightarrow{b}|=\sqrt{1+4+4}$
 
             $|\overrightarrow{b}| =\sqrt{9}$

             $|\overrightarrow{b}| =3$

      3. Menggunakan definisi perkalian titik
         $\overrightarrow{a}.\overrightarrow{b} =|\overrightarrow{a}|\overrightarrow{b}| cos \theta$

         $cos\theta=\frac{\overrightarrow{a}.\overrightarrow{b}}{|\overrightarrow{a}| |\overrightarrow{b}|}$

            $cos \theta=\frac{-61}{\sqrt{14}.3}$

            $cos \theta=\frac{-2}{\sqrt{14}}$
          
            $cos \theta=-\frac{1}{7}\sqrt{14}$

            $\theta=arccos(-\frac{\sqrt{14}}{7})=122,3 derajat$




# BAB 4: GARIS DALAM RUANG DIMENSI TIGA (3D)

## 4.1 KONSEP DASAR VEKTOR ARAH DALAM RUANG 3D
Pada geometri analitik bidang atau ruang dimensi dua ($R^2$), 
kemiringan atau inklinasi suatu garis lurus dapat dinyatakan secara sederhana menggunakan satu nilai skalar yang disebut gradien ($m$). Nilai gradien ini diperoleh dari rasio perubahan nilai vertikal terhadap perubahan nilai horizontal ($\Delta y / \Delta x$). Namun, karakteristik geometris ini berubah secara drastis ketika kita beralih ke ruang dimensi tiga ($R^3$). Di dalam ruang 3D, sebuah garis memiliki kebebasan untuk condong atau miring ke berbagai arah ruang yang tak terbatas jumlahnya. Oleh karena itu, konsep kemiringan berbasis skalar tunggal kehilangan relevansi dan validitas matematisnya.

Untuk menentukan arah spesifik dari suatu garis lurus di dalam ruang dimensi tiga, kita memerlukan instrumen matematika berupa vektor. Arah suatu garis dalam ruang 3D ditentukan secara unik oleh sebuah vektor non-nol yang posisinya sejajar atau berimpit dengan garis tersebut. Vektor inilah yang disebut sebagai **Vektor Arah** ($\vec{v}$). 

Secara formal, sebuah garis lurus $L$ di dalam ruang dimensi tiga dapat didefinisikan secara tunggal dan spesifik jika dan hanya jika diketahui dua elemen geometris berikut:
1. Sebuah titik tetap $P_0(x_0, y_0, z_0)$ yang terletak tepat pada lintasan garis $L$.
2. Sebuah vektor arah non-nol $\vec{v} = v_1\hat{i} + v_2\hat{j} + v_3\hat{k} = \langle v_1, v_2, v_3 \rangle$ yang sejajar dengan garis $L$.



> **CONTOH SOAL: KONSEP VEKTOR ARAH**
> **Soal:**
> Sebuah garis lurus $L$ di dalam ruang dimensi tiga diketahui memiliki sifat sejajar dengan vektor posisi yang dibentuk dari titik asal $O(0,0,0)$ menuju ke titik koordinat $M(4, -2, 6)$. Jika garis $L$ tersebut wajib melalui sebuah titik tetap $A(1, 3, 2)$, tentukan komponen vektor arah dari garis $L$ tersebut dan formulasikan representasi geometrisnya.
> <div align="center">
  <img src="https://i.ibb.co.com/TBpywFhY/4-1.png" width="500">
   
</div>

> **Penyelesaian:**
> * **Langkah 1:** Pahami sifat kesejajaran objek. Karena garis $L$ dinyatakan sejajar dengan vektor posisi $\overrightarrow{OM}$, maka berdasarkan hukum keselarasan arah, komponen vektor arah $\vec{v}$ dari garis $L$ secara langsung dapat diwakili oleh komponen vektor $\overrightarrow{OM}$ itu sendiri.
> * **Langkah 2:** Hitung komponen-komponen spasial dari vektor $\vec{v}$ melalui pengurangan koordinat titik ujung (*terminal point*) dengan titik pangkal (*initial point*):
>   $$\vec{v} = \overrightarrow{OM} = \langle 4 - 0, -2 - 0, 6 - 0 \rangle = \langle 4, -2, 6 \rangle$$
> * **Langkah 3:** Identifikasi parameter koordinat akhir. Titik acuan tetap yang dilalui garis adalah $P_0 = A(1, 3, 2)$ dengan komponen $x_0 = 1$, $y_0 = 3$, $z_0 = 2$. Vektor arah yang mengontrol kemiringan ruang dari garis ini adalah $\vec{v} = \langle 4, -2, 6 \rangle$, di mana nilai komponen arah skalarnya adalah $v_1 = 4$, $v_2 = -2$, dan $v_3 = 6$.

## 4.2 PERSAMAAN VEKTOR GARIS RECTILINEAR 3D
Setelah memahami peran vital dari vektor arah, kita dapat menurunkan persamaan matematika formal dari sebuah garis di ruang 3D. Pendekatan pertama dilakukan melalui analisis vektor posisi. Misalkan terdapat sebuah titik variabel bebas $P(x, y, z)$ yang terletak di sembarang posisi pada garis $L$. Garis $L$ ini sendiri memuat titik tetap $P_0(x_0, y_0, z_0)$ dan bergerak searah dengan vektor $\vec{v} = \langle v_1, v_2, v_3 \rangle$.

Jika kita menarik vektor dari titik asal $O(0,0,0)$ ke titik tetap $P_0$, kita mendapatkan vektor posisi $\vec{r_0} = \langle x_0, y_0, z_0 \rangle$. Dengan cara yang sama, vektor posisi untuk titik variabel $P$ adalah $\vec{r} = \langle x, y, z \rangle$. Berdasarkan operasi penjumlahan vektor segitiga, vektor yang menghubungkan titik $P_0$ langsung ke titik variabel $P$ dapat dituliskan sebagai:
$$\overrightarrow{P_0P} = \vec{r} - \vec{r_0}$$

Secara geometris, karena titik $P_0$ dan $P$ keduanya berada pada garis $L$, maka vektor $\overrightarrow{P_0P}$ haruslah segaris (*collinear*) dan sejajar dengan vektor arah $\vec{v}$. Dua buah vektor dikatakan sejajar jika dan hanya jika salah satu vektor merupakan hasil perkalian skalar dari vektor lainnya. Oleh karena itu, terdapat suatu parameter bilangan real $t$ ($-\infty < t < \infty$) sedemikian rupa sehingga memenuhi hubungan:
$$\overrightarrow{P_0P} = t\vec{v}$$

Substitusikan nilai $\overrightarrow{P_0P} = \vec{r} - \vec{r_0}$ ke dalam persamaan di atas:
$$\vec{r} - \vec{r_0} = t\vec{v}$$
$$\vec{r} = \vec{r_0} + t\vec{v}$$

Persamaan di atas merupakan **Persamaan Vektor dari Garis dalam Ruang 3D**. Setiap kali nilai parameter $t$ diubah dengan bilangan real apa pun, vektor posisi $\vec{r}$ akan menunjuk ke suatu titik spesifik di sepanjang garis $L$.

 > **CONTOH SOAL: PERSAMAAN VEKTOR**
> Susunlah persamaan vektor untuk sebuah garis lurus $L$ dalam ruang dimensi tiga yang melintasi titik koordinat $P_0(-2, 0, 4)$ serta memiliki arah yang sejajar dengan vektor $\vec{v} = 2\hat{i} + 4\hat{j} - 2\hat{k}$.
> <div align="center">
  <img src="https://i.ibb.co.com/fbQxRfv/4-2.png" width="500">
   
</div>

> **Penyelesaian:**
> * **Langkah 1:** Transformasikan koordinat titik tetap $P_0$ menjadi bentuk komponen vektor posisi awal $\vec{r_0}$:
>   $$\vec{r_0} = \langle -2, 0, 4 \rangle$$
> * **Langkah 2:** Tuliskan komponen dari vektor arah $\vec{v}$ yang diberikan ke dalam notasi kurung siku standar:
>   $$\vec{v} = \langle 2, 4, -2 \rangle$$
> * **Langkah 3:** Substitusikan komponen vektor $\vec{r_0}$ dan $\vec{v}$ ke dalam kerangka rumus umum persamaan vektor $\vec{r} = \vec{r_0} + t\vec{v}$:
>   $$\vec{r}(t) = \langle -2, 0, 4 \rangle + t\langle 2, 4, -2 \rangle$$
>   $$\vec{r}(t) = \langle -2 + 2t, 4t, 4 - 2t \rangle$$

## 4.3 PERSAMAAN PARAMETRIK GARIS DALAM RUANG
Meskipun persamaan vektor memberikan landasan konsep yang kuat, dalam kalkulus analitis kita sering kali membutuhkan persamaan skalar terpisah untuk masing-masing sumbu koordinat. Kita dapat menurunkan persamaan ini dengan mengurai komponen-komponen pada persamaan vektor $\vec{r} = \vec{r_0} + t\vec{v}$.

Mari kita tulis persamaan vektor tersebut dalam bentuk matriks komponen baris:
$$\langle x, y, z \rangle = \langle x_0, y_0, z_0 \rangle + t\langle v_1, v_2, v_3 \rangle$$

Lakukan operasi perkalian skalar $t$ dan penjumlahan vektor pada ruas kanan persamaan:
$$\langle x, y, z \rangle = \langle x_0 + tv_1, y_0 + tv_2, z_0 + tv_3 \rangle$$

Berdasarkan prinsip kesamaan dua buah vektor, dua vektor dikatakan sama jika dan hanya jika seluruh komponen yang bersesuaian pada kedua ruas bernilai sama. Dengan menyamakan komponen pada sumbu $X$, sumbu $Y$, dan sumbu $Z$, kita memperoleh sistem **Persamaan Parametrik Garis 3D**:
$$x = x_0 + tv_1$$
$$y = y_0 + tv_2$$
$$z = z_0 + tv_3$$

Di mana variabel $t$ bertindak sebagai parameter bebas real yang jangkauan nilainya membentang dari $-\infty$ hingga $+\infty$.

> **CONTOH SOAL: PERSAMAAN PARAMETRIK**
> Carilah sistem persamaan parametrik dari sebuah garis lurus di ruang 3D yang melintasi dua titik eksternal yaitu titik $A(5, 1, 3)$ dan titik $B(2, 6, -1)$.
> <div align="center">
  <img src="https://i.ibb.co.com/nq00hQqg/4-3.png" width="500">
   
</div>

> **Penyelesaian:**
> * **Langkah 1:** Tentukan vektor arah $\vec{v}$ dengan menghitung vektor perpindahan dari titik $A$ ke titik $B$ ($\overrightarrow{AB}$):
>   $$\vec{v} = \overrightarrow{AB} = \langle 2 - 5, 6 - 1, -1 - 3 \rangle = \langle -3, 5, -4 \rangle$$
>   Dari perhitungan ini, kita peroleh nilai komponen arah: $v_1 = -3$, $v_2 = 5$, dan $v_3 = -4$.
> * **Langkah 2:** Pilih titik $A(5, 1, 3)$ sebagai acuan titik tetap $P_0(x_0, y_0, z_0)$, maka kita peroleh: $x_0 = 5$, $y_0 = 1$, dan $z_0 = 3$.
> * **Langkah 3:** Substitusikan nilai konstanta titik tetap dan komponen arah ke dalam rumus baku persamaan parametrik:
>   $$x = 5 - 3t, \quad y = 1 + 5t, \quad z = 3 - 4t$$
>
  

## 4.4 PERSAMAAN SIMETRIS GARIS DALAM RUANG
Terdapat metode alternatif untuk menyatakan sebuah garis di dalam ruang tanpa melibatkan parameter $t$, yaitu dengan menggunakan hubungan rasio spasial. Pendekatan ini dapat dilakukan apabila seluruh komponen skalar pada vektor arah memiliki nilai non-nol ($v_1 \neq 0, v_2 \neq 0, v_3 \neq 0$).

Perhatikan kembali sistem persamaan parametrik dasar yang kita miliki:
1. Dari persamaan $x = x_0 + tv_1$, jika kita isolasi variabel $t$, didapatkan: $t = \frac{x - x_0}{v_1}$
2. Dari persamaan $y = y_0 + tv_2$, jika kita isolasi variabel $t$, didapatkan: $t = \frac{y - y_0}{v_2}$
3. Dari persamaan $z = z_0 + tv_3$, jika kita isolasi variabel $t$, didapatkan: $t = \frac{z - z_0}{v_3}$

Karena parameter $t$ pada ketiga persamaan di atas merujuk pada satu nilai waktu atau titik kontemporer yang sama di sepanjang garis, maka kita dapat mengeliminasi variabel $t$ dan menyamakan ketiga nilai rasio tersebut secara kontinu:
$$\frac{x - x_0}{v_1} = \frac{y - y_0}{v_2} = \frac{z - z_0}{v_3}$$

Hubungan kesamaan rasio tripel di atas dinamakan sebagai **Persamaan Simetris Garis 3D**.

*Catatan Pengecualian:* Jika salah satu komponen vektor arah bernilai nol, misalnya $v_3 = 0$, maka kita tidak boleh melakukan pembagian dengan nol. Persamaan simetrisnya dimodifikasi dengan cara memisahkan komponen yang bernilai nol tersebut:
$$\frac{x - x_0}{v_1} = \frac{y - y_0}{v_2}, \quad z = z_0$$

> **CONTOH SOAL: PERSAMAAN SIMETRIS** 
> **Soal:**
> Diketahui sebuah garis lurus dalam ruang memiliki struktur persamaan parametrik $x = 1 + 2t$, $y = 3 - 4t$, dan $z = 5 + 6t$. Ubahlah bentuk persamaan tersebut menjadi bentuk persamaan simetris.
> <div align="center">
  <img src="https://i.ibb.co.com/4wf8Wvj7/4-4.png" width="500">
   
</div>

> **Penyelesaian:**
> * **Langkah 1:** Identifikasi koordinat titik tetap ($x_0, y_0, z_0$) dan nilai komponen vektor arah ($v_1, v_2, v_3$) dari persamaan parametrik:
>   Dari $x = 1 + 2t \implies x_0 = 1, v_1 = 2$
>   Dari $y = 3 - 4t \implies y_0 = 3, v_2 = -4$
>   Dari $z = 5 + 6t \implies z_0 = 5, v_3 = 6$
> * **Langkah 2:** Masukkan seluruh nilai komponen skalar tersebut ke dalam rumus dasar persamaan simetris:
>   $$\frac{x - 1}{2} = \frac{y - 3}{-4} = \frac{z - 5}{6}$$
> * **Langkah 3:** Sederhanakan bagian penyebut dengan mengalikan seluruh penyebut dengan angka 2:
>   $$\frac{x - 1}{1} = \frac{y - 3}{-2} = \frac{z - 5}{3}$$

## 4.5 PERSAMAAN SEGMEN GARIS TERBATAS
Dalam berbagai aplikasi rekayasa, fisika, dan grafika komputer, kita sering kali tidak berhadapan dengan sebuah garis lurus utuh yang panjangnya tak terbatas. Sering kali kita hanya perlu menganalisis sepotong bagian garis yang dibatasi oleh dua buah titik, yaitu dimulai dari titik awal $P_0(x_0, y_0, z_0)$ dan berakhir di titik tujuan $P_1(x_1, y_1, z_1)$. Objek geometri terikat ini disebut sebagai **Segmen Garis** (*Line Segment*).

Untuk membentuk persamaannya, kita tentukan dahulu vektor arah yang menghubungkan $P_0$ langsung ke $P_1$:
$$\vec{v} = \overrightarrow{P_0P_1} = \vec{r_1} - \vec{r_0} = \langle x_1 - x_0, y_1 - y_0, z_1 - z_0 \rangle$$

Substitusikan vektor arah spesifik ini ke dalam landasan persamaan vektor dasar $\vec{r} = \vec{r_0} + t\vec{v}$:
$$\vec{r}(t) = \vec{r_0} + t(\vec{r_1} - \vec{r_0})$$

Lakukan perluasan aljabar dan kelompokkan suku-suku berdasarkan vektor posisinya:
$$\vec{r}(t) = \vec{r_0} + t\vec{r_1} - t\vec{r_0}$$
$$\vec{r}(t) = (1 - t)\vec{r_0} + t\vec{r_1}$$

Agar persamaan di atas menghasilkan sepotong segmen garis yang presisi dan tidak meluas tanpa batas, kita wajib menerapkan batasan nilai parameter $t$ pada interval tertutup:
$$0 \leq t \leq 1$$

* Jika kita memasukkan nilai $t = 0$, maka persamaan menghasilkan $\vec{r}(0) = \vec{r_0}$ (posisi tepat berada di titik awal $P_0$).
* Jika kita memasukkan nilai $t = 1$, maka persamaan menghasilkan $\vec{r}(1) = \vec{r_1}$ (posisi tepat berada di titik akhir $P_1$).


> **CONTOH SOAL: SEGMEN GARIS**
> **Soal:**
> Formulasikan persamaan parametrik yang memodelkan segmen ruas garis dengan ujung-ujung yang mengikat dari titik awal $P_0(2, 4, -1)$ hingga mencapai titik akhir $P_1(5, 0, 7)$ di dalam ruang 3D.
>     <div align="center">
  <img src="https://i.ibb.co.com/YBg0V8gg/4-5.png" width="500">
   
</div>

> **Penyelesaian:**
> * **Langkah 1:** Catat elemen koordinat pada masing-masing titik ujung segmen:
>   $$x_0 = 2, y_0 = 4, z_0 = -1 \quad \text{dan} \quad x_1 = 5, y_1 = 0, z_1 = 7$$
> * **Langkah 2:** Gunakan perumusan komponen segmen garis $x = x_0 + t(x_1 - x_0)$ untuk masing-masing sumbu koordinat:
>   $$x = 2 + t(5 - 2) = 2 + 3t$$
>   $$y = 4 + t(0 - 4) = 4 - 4t$$
>   $$z = -1 + t(7 - (-1)) = -1 + 8t$$
> * **Langkah 3:** Gabungkan ketiga komponen skalar tersebut beserta dengan syarat batas interval:
>   $$x = 2 + 3t, \quad y = 4 - 4t, \quad z = -1 + 8t \quad \text{di mana } 0 \leq t \leq 1$$

## 4.6 KLASIFIKASI HUBUNGAN GEOMETRIS ANTARA DUA BUAH GARIS

Di dalam ruang dimensi dua ($R^2$), 
dua buah garis yang berbeda hanya memiliki dua kemungkinan hubungan posisi: jika tidak sejajar, kedua garis tersebut pasti akan berpotongan di suatu titik. Namun, di dalam ruang dimensi tiga ($R^3$), terdapat tiga kemungkinan hubungan posisi antara dua buah garis yang berbeda ($L_1$ dengan vektor arah $\vec{v}_1$ dan $L_2$ dengan vektor arah $\vec{v}_2$):

### 4.6.1 Garis-Garis Sejajar (*Parallel Lines*)
Dua buah garis dikatakan sejajar jika dan hanya jika vektor arah dari kedua garis tersebut memiliki orientasi yang sama atau berlawanan arah, yang ditandai dengan sifat kelipatan skalar:
$$\vec{v_1} = k\vec{v_2}, \quad \text{di mana } k \in R \text{ dan } k \neq 0$$

### 4.6.2 Garis-Garis Berpotongan (*Intersecting Lines*)
Dua buah garis dikatakan berpotongan jika keduanya tidak sejajar, namun memiliki satu titik persekutuan tunggal $P(x,y,z)$ yang sama. Untuk membuktikan hubungan ini, kita harus menyelesaikan sistem persamaan parametrik dari kedua garis secara simultan menggunakan dua variabel parameter yang berbeda (misalnya parameter $t$ untuk garis $L_1$ dan parameter $s$ untuk garis $L_2$).

### 4.6.3 Garis-Garis Bersilangan (*Skew Lines*)
Garis bersilangan merupakan fenomena geometris yang unik dan hanya terjadi pada ruang dimensi tiga atau lebih tinggi. Dua buah garis dikatakan bersilangan jika keduanya **tidak saling sejajar** dan **tidak pernah berpotongan** meskipun ditarik sepanjang apa pun. Hal ini terjadi karena kedua garis berada pada dua lapisan bidang sejajar yang berbeda di dalam ruang.
> **CONTOH SOAL: HUBUNGAN DUA GARIS**
> **Soal:**
> Lakukan analisis analitis menyeluruh untuk menentukan hubungan geometris antara dua garis berikut, apakah berpotongan atau bersilangan:
> $$L_1: x = 1 + t, \quad y = -2 + 3t, \quad z = 4 - t$$
> $$L_2: x = 2s, \quad y = 3 + s, \quad z = -3 + 4s$$
> <div align="center">
  <img src="https://i.ibb.co.com/cXNHXcFC/4-6.png" width="500">
   
</div>

> **Penyelesaian:**
> * **Langkah 1 (Uji Kesejajaran):** Ekstrak vektor arah masing-masing komponen: $\vec{v_1} = \langle 1, 3, -1 \rangle$ dan $\vec{v_2} = \langle 2, 1, 4 \rangle$. Periksa perbandingan rasionya:
>   $$\frac{1}{2} \neq \frac{3}{1} \neq \frac{-1}{4}$$
>   Karena rasio antar komponennya tidak bernilai konstan, maka **Kedua garis tidak sejajar**.
> * **Langkah 2 (Uji Titik Potong pada Sumbu X dan Y):**
>   Samakan komponen $x$: $1 + t = 2s \implies t = 2s - 1 \quad (\text{Persamaan i})$
>   Samakan komponen $y$: $-2 + 3t = 3 + s \quad (\text{Persamaan ii})$
>   Substitusikan Persamaan (i) ke dalam Persamaan (ii):
>   $$-2 + 3(2s - 1) = 3 + s \implies 5s = 8 \implies s = 1.6$$
>   Setelah itu, hitung nilai parameter $t$: $t = 2(1.6) - 1 = 2.2$
> * **Langkah 3 (Uji Konsistensi Nilai pada Sumbu Z):**
>   Uji pasangan nilai parameter $t = 2.2$ dan $s = 1.6$ pada komponen $z$:
>   Untuk Garis $L_1 \implies z = 4 - t = 4 - 2.2 = 1.8$
>   Untuk Garis $L_2 \implies z = -3 + 4s = -3 + 4(1.6) = 3.4$
>   Karena hasil perhitungan koordinat $z$ menghasilkan nilai yang berbeda ($1.8 \neq 3.4$), maka sistem persamaan tersebut mengalami kontradiksi (inkonsisten).
> * **Kesimpulan:** Karena kedua garis tidak memiliki arah yang sejajar dan tidak memiliki titik potong persekutuan, maka hubungan antara garis $L_1$ dan $L_2$ adalah **Bersilangan** (*Skew Lines*).
>
## 4.7 PERHITUNGAN JARAK TEGAK LURUS DARI SEBUAH TITIK KE GARIS
Misalkan terdapat sebuah titik $S$ yang berada di luar sebuah garis lurus $L$ di dalam ruang 3D. Garis $L$ tersebut diketahui memuat titik tetap $P_0$ dan bergerak searah dengan vektor arah $\vec{v}$. Jarak terpendek atau jarak tegak lurus $d$ dari titik $S$ menuju garis $L$ dapat ditentukan dengan memanfaatkan operasi perkalian silang (*cross product*).

Perhatikan segitiga siku-siku yang dibentuk oleh titik tetap $P_0$, titik luar $S$, dan proyeksi tegak lurus titik $S$ pada garis $L$. Panjang sisi miring dari segitiga ini diwakili oleh magnitudo dari vektor $\overrightarrow{P_0S}$. Jika $\theta$ menyatakan sudut lancip yang terbentuk antara vektor $\overrightarrow{P_0S}$ dengan vektor arah garis $\vec{v}$, maka berdasarkan perbandingan trigonometri, jarak tegak lurus $d$ dapat dituliskan sebagai:
$$d = |\overrightarrow{P_0S}| \sin \theta$$

Berdasarkan definisi geometris dari operasi perkalian silang antara dua buah vektor, magnitudo dari hasil kali silang vektor $\overrightarrow{P_0S}$ dengan vektor arah $\vec{v}$ memenuhi hubungan persamaan berikut:
$$|\overrightarrow{P_0S} \times \vec{v}| = |\overrightarrow{P_0S}| |\vec{v}| \sin \theta$$

Substitusikan hubungan trigonometri $| \overrightarrow{P_0S} | \sin \theta = d$ ke dalam persamaan perkalian silang di atas:
$$|\overrightarrow{P_0S} \times \vec{v}| = d \cdot |\vec{v}|$$

Dengan mengisolasi variabel $d$, kita mendapatkan rumus baku untuk menghitung **Jarak Titik ke Garis dalam Ruang 3D**:
$$d = \frac{|\overrightarrow{P_0S} \times \vec{v}|}{|\vec{v}|}$$

> **CONTOH SOAL: JARAK TITIK KE GARIS**
> **Soal:**
> Hitunglah jarak tegak lurus $d$ yang membentang dari sebuah titik luar $S(1, 1, 5)$ menuju ke sebuah garis lurus $L$ yang memiliki rumusan persamaan parametrik $x = 1 + 2t$, $y = -1 + 3t$, dan $z = 4 + t$.
> <div align="center">
  <img src="https://i.ibb.co.com/fYnZ4QxT/4-7.png" width="500">
   
</div>

> **Penyelesaian:**
> * **Langkah 1:** Ekstrak data dari persamaan parametrik garis $L$: Titik tetap $P_0(1, -1, 4)$ dan vektor arah $\vec{v} = \langle 2, 3, 1 \rangle$.
> * **Langkah 2:** Hitung komponen vektor posisi $\overrightarrow{P_0S}$ yang menghubungkan titik tetap $P_0$ ke titik luar $S$:
>   $$\overrightarrow{P_0S} = \langle 1 - 1, 1 - (-1), 5 - 4 \rangle = \langle 0, 2, 1 \rangle$$
> * **Langkah 3:** Hitung operasi perkalian silang (*cross product*) $\overrightarrow{P_0S} \times \vec{v}$ menggunakan determinan matriks $3 \times 3$:
>   $$\overrightarrow{P_0S} \times \vec{v} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 0 & 2 & 1 \\ 2 & 3 & 1 \end{vmatrix} = \hat{i}(2 - 3) - \hat{j}(0 - 2) + \hat{k}(0 - 4) = \langle -1, 2, -4 \rangle$$
> * **Langkah 4:** Hitung nilai magnitudo (panjang) dari vektor hasil perkalian silang dan vektor arah $\vec{v}$:
>   $$|\overrightarrow{P_0S} \times \vec{v}| = \sqrt{(-1)^2 + (2)^2 + (-4)^2} = \sqrt{21}$$
>   $$|\vec{v}| = \sqrt{(2)^2 + (3)^2 + (1)^2} = \sqrt{14}$$
> * **Langkah 5:** Masukkan kedua nilai magnitudo tersebut ke dalam rumus jarak $d$:
>   $$d = \frac{\sqrt{21}}{\sqrt{14}} = \sqrt{\frac{3}{2}} = \frac{1}{2}\sqrt{6} \approx 1.22$$
>


## DAFTAR PUSTAKA ACUAN DAN HALAMAN SUMBER

* **Riddle, Douglas F.** (1996). *Analytic Geometry, Sixth Edition*. Boston: PWS Publishing Company.
    * *Rujukan Sub-bab 4.1 & 4.2 (Transformasi Koordinat, Teori Vektor Arah, dan Penurunan Komponen Vektor Ruang)* $\rightarrow$ Diadopsi dan disintesis secara analitis dari Bab 6 (*Transformation of Coordinates and Vectors in Space*), **Halaman 195–201**.
* **Stewart, James.** (2012). *Calculus: Early Transcendentals, Seventh Edition (Multivariable Volume)*. Belmont: Brooks/Cole Cengage Learning.
    * *Rujukan Sub-bab 4.3, 4.4, & 4.6 (Sistem Persamaan Parametrik, Rasio Kesamaan Simetris, dan Teorema Klasifikasi Garis Bersilangan)* $\rightarrow$ Diadopsi secara akurat dari Chapter 12 (*Vectors and the Geometry of Space*), Section 12.5 (*Lines and Planes in Space*), **Halaman 559–561**.
* **Thomas Jr., George B., Weir, Maurice D., & Hass, Joel.** (2014). *Thomas' Calculus: Early Transcendentals, Thirteenth Edition*. Boston: Pearson Education, Inc.
    * *Rujukan Sub-bab 4.5 & 4.7 (Formulasi Batasan Parameter Ruas Garis Tertentu dan Penurunan Jarak Berbasis Operasi Cross-Product Vektor)* $\rightarrow$ Diadopsi secara ketat dari Chapter 12 (*Vectors and the Geometry of Space*), Section 12.5, **Halaman 732–735**.
