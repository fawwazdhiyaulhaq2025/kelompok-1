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

A. a. Rumus Jarak dua titik (2D)
Jika diketahui titik $A(x_1, y_2)$ dan $B(x_2, y_2)$, maka jarak AB dirumuskan sebagai:

$d=\sqrt{(x^2-x^1)^2+(y_2-y_1)^2}$

Keterangan:
- $x_2 ​- x_1$ = selisih koordinat $x$
- $y_2 - y_1$ = selisih koordinat $y$

> CONTOH SOAL:
>Tentukan jarak titik $A(2, 3)$ dan B$(7, 15)$
Penyelesaian: 
Diketahui: 
$x_1=2$
$x_2=7$
$y_1=3$
$y_2=15$
substitusi ke dalam rumus:
$d=\sqrt{(7−2)^2+(15-7)^2}$
$d=\sqrt{5^2+12^2}$
$d=\sqrt{25+144}$
$d=\sqrt{169}$
$d=13$
jadi, jarak antara titik adalah $13$.

   b. Jarak dua titik (3D)
Pada ruang tiga dimensi, titk dinyatakan sebagai $(x, y, z)$. Konsep jarak diperluas dengan menambahkan sumbu $z$.

* Rumus jarak dua titik (3D)
Jika diketahui titik $A(x_1, y_2, z_3)$ dan $B(x_1, y_2, z_3)$, maka jarak $d$ diantara keduanya adalah:

$d = \sqrt{(x2 - x1)^2 + (y2 - y1)^2 + (z2 - z1)^2}$

> CONTOH SOAL:
> Tentukan jarak titik A $(1, 2, 3)$ dan B $(4, 6, 15)$
Penyelesaian:
Diketahui: 
$x_1=1$, 
$x_2=4$, 
$y_1=2$, 
$y_2=6$, 
$z_1=3$, 
$z_2=15$, 
substitusi ke dalam rumus:
$d = \sqrt{(4 - 1)^2 + (6 - 2)^2 + (15 - 3)^2}$
$d = \sqrt{3^2 + 4^2 + 12^2}$
$d = \sqrt{9 + 16 + 144}$
$d = \sqrt{169}$
$d = 13$
jadi, jarak titk  antara $A$ dan $B$ adalah $13$.

B. a. Jarak titk ke garis (2D)
Jarak titik ke garis adalah panjang ruas garis terpendek dari titk menuju garis, yaitu garis tegak lurus terhadap garis tersebut. 
* Persamaan titik ke garis
Garis biasa ditulis dengan persamaan $ax + by + c = 0$, dan untuk menghitung  jarak titik ke garis digunakan rumus:

$d = \frac{|ax0 + by0 + c|}\sqrt{(a² + b²)}$

Contoh soal
Tentukan jarak titik $P(2, 1)$ terhadap garis 

$3x + 4y - 10 = 0$

Penyelesaian:
Diketahui:
$A=3$, $B=4$, $C-10$
$(x_1, y_1) = (2, 1)$
substitusikan kedalam rumus:
$d = \frac{|3(2) + 4(1) - 10|}\sqrt{(3² + 4²)}$
$d = \frac{|6 + 4 - 10|}\sqrt{(9 + 16)}$
$d = \frac{|0|}\sqrt{(25)}$
$d = 0$
jadi, jarak titik $P(2, 1)$ terhadap garis $3x + 4y - 10 = 0$ adalah $0$

  b. Jarak titik ke garis (3D)
Dalam ruang tiga dimensi, garis biasanya dinyatakan dalam bentuk parametrik atau vektor. Dalam ruang tiga dimensi garis biasanya ditulis dalam bentuk: 

$\frac{x−x_1}​​{a} = \frac{y−y_1​​}{b} = \frac{z−z_1}{c}$​​

* Rumus jarak titik ke garis (3D)
Jika titk $A$ berada di garis $A(x_1, y_2, z_3)$ dan $v$ adalah vektor arah garis $v=(a,b,c)$, maka jarak titik $P$ ke garis dapat dicari menggunakan:
$d=\frac{∣AP×v∣}{​∣v∣}$

> CONTOH SOAL:
> Tentukan jarak titik P(1, 2, 3) ke garis

$\frac{x}{1}​=\frac{y​}{2}=\frac{z}​{2}$

Penyelesaian:
Diketahui:
$v=(1,2,2)$
$A(0,0,0)$
$AP=(1,2,3)$
maka:
AP×v=i j k
     1 2 3
     1 2 2 
    =(−2,1,0)
substitusikan ke dalam rumus:
$d=\frac{∣AP×v∣}​{∣v∣}$
$d=\frac\sqrt({(−2)^2+1^2+0^2}x\sqrt1^2+2^2+2^2}{1^2+2^2+2^2})$
$d=\sqrt{5}x3$


C. Jarak titik ke bidang (3D)
Bidang dalam ruang dinyatakan dalam bentuk $ax + by + cz + d = 0$ untuk titik $P(x_1, y_1, z_1)$.
* Rumus untuk jarak titik ke bidang
Jika titik $P(x_1,y_1,z_1) dan bidang $ax+by+cz+d=0$, maka jaraknya adalah:

$d = \frac{|ax1 + by1 + cz1 + d|}\sqrt{(a²+b²+c²)}$

> CONTOH SOAL:
Tentukan jarak titik $P(1,2,3)$ terhadap bidang:

$2x−y+2z−5=0$

Penyelesaian:
$d = \frac{|2(1) + 1(2) + 2(3) + 5|}\sqrt{(2²-1²+2²)}$
$d = \frac{|2 - 2 + 6 - 5|}\sqrt{(4+1+4)}$
$d = \frac{1}{3}$

D. Jarak dua garis 
* Sejajar dalam ruang
Dua garis sejajar memiliki vektor arah yang sama atau kelipatan satu sama lain.

Jika dua garis sejajar:


> CONTOH SOAL:


* Bersilangan (Skew Lines)
Garis bersilangan adalah garis yang tidak sejajar dan tidak berpotongan. 
	​
Formula rumus:


> CONTOH SOAL:


LATIHAN SOAL 
1. Berapakah jarak antara titik $P(2,3)$ dan $Q(5,7)$?
a. $4$ satuan
b. $5$ satuan
c. $6$ satuan
d. $7$ satuan

2. Hitunglah jarak antara titik $A(-1,2)$ dan $B(3,-1)$.
a. $4$ satuan
b. $5$ satuan
c. $√13$ satuan
d. $√17$ satuan

3. Tentukan jarak titik asal $(0,0)$ ke titik $D(6,8)$.
a. $√50$ satuan
b. $√72$ satuan
c. $10$ satuan
d. $14$ satuan

4. Jika titik $E(x,5)$ dan $F(2,1)$ berjarak $5$ satuan, maka nilai $x$ yang mungkin adalah…
a. $x = 2$ atau $x = 8$
b. $x = 0$ atau $x = 4$
c. $x = -1$ atau $x = 5$
d. $x = 1$ atau $x = 3$

5. Berapakah jarak antara titik $P(1,2,3)$ dan $Q(4,5,6)$ di ruang tiga dimensi?
a. $√18$ satuan
b. $√27$ satuan
c. $3√3$ satuan
d. $√45$ satuan

6. Jarak antara titik $(a, 0)$ dan $(0, b)$ adalah…
a. $|a+b|$
b. $|a-b|$
c. $√(a²+b²)$
d. $a+b$

7. Titik $(k, 3)$ berjarak $5$ satuan dari titik $(1, 0)$. Nilai $k$ yang mungkin adalah…
a. $k = 4$ atau $k = -2$
b. $k = -3$ atau $k = 5$
c. $k = 0$ atau $k = 2$
d. $k = 1$ atau $k = 4$

8. Jika titik $A(2,y)$ dan $B(5,-1)$ berjarak $3√2$ satuan, maka nilai $y$ yang mungkin adalah…
y = 1 atau y = -3
y = 0 atau y = -2
y = 2 atau y = -4
y = -1 atau y = -5

9. Titik P(3,4) dan Q(x,y). Jika titik asal O(0,0) adalah titik tengah ruas garis PQ, berapakah jarak PQ?
5 satuan
√50 satuan
√75 satuan
10 satuan

10. Sebuah segitiga ABC memiliki koordinat A(1,1), B(4,1), dan C(4,5). Berapakah panjang sisi AC?
3 satuan
4 satuan
5 satuan
√34 satuan

11. Sebuah lingkaran berpusat di (2,3) dan melalui titik (5,7). Berapakah jari-jari lingkaran tersebut?
3 satuan
√13 satuan
5 satuan
√41 satuan

12. Manakah pernyataan yang paling tepat mengenai rumus jarak titik ke titik?
Rumus jarak hanya berlaku untuk titik-titik pada sumbu koordinat.
Rumus jarak titik ke titik hanya digunakan untuk mencari panjang sisi miring segitiga.
Rumus jarak titik ke titik merupakan generalisasi dari Teorema Pythagoras.
Rumus jarak hanya dapat digunakan pada bidang 2 dimensi.

13. Jarak titik (a,b,c) ke titik asal (0,0,0) di ruang tiga dimensi adalah…
|a+b+c|
a+b+c
√(a²+b²+c²)
√(a²+b²)

14. Dua titik berada pada sumbu X, yaitu P(x1, 0) dan Q(x2, 0). Jarak PQ adalah…
x1+x2
x2-x1
|x2-x1|
√(x1²+x2²)

15. Dua titik berada pada bidang YZ, yaitu P(0, y1, z1) dan Q(0, y2, z2). Jarak PQ adalah…
√((y1-z1)² + (y2-z2)²)
√((y2-y1)²)
√((y2-y1)² + (z2-z1)²)
|y2-y1| + |z2-z1|

16. Titik A(2,3) dan B(5,k). Jika jarak AB adalah 3 satuan, maka nilai k adalah…
k = 0
k = 3
k = 6
k = 9

17. Jika (x-1)² + (y-2)² = 25, maka ini berarti titik (x,y) berjarak berapa satuan dari titik (1,2)?
√5 satuan
√25 satuan
5 satuan
25 satuan

18. Rumus jarak antara dua titik (x1,y1) dan (x2,y2) adalah…
|x2-x1| + |y2-y1|
(x2-x1)² + (y2-y1)²
√((x2-x1)² + (y2-y1)²)
√((x2+x1)² + (y2+y1)²)

19. Jika titik A(1, -2), B(1, 3), dan C(k, 0) membentuk segitiga sama kaki dengan panjang AB = BC, maka nilai k yang mungkin adalah…
k = 1 atau k = -1
k = 2 atau k = -2
k = 5 atau k = -3
k = 0 atau k = 4

20. Pilih pasangan titik yang memiliki jarak $5$ satuan:
a. $(1,1)$ dan $(2,3)$
b. $(0,0)$ dan $(3,4)$
c. $(2,5)$ dan $(4,7)$
d. $(-1,0)$ dan $(3,2)$

21. Hitung jarak antara titik $P(-3, 5)$ dan $Q(4, -2)$.
22. Sebuah titik $A(x, 4)$ berjarak $10$ satuan dari titik $B(2, -2)$. Tentukan semua nilai $x$ yang mungkin.
23. Jelaskan mengapa rumus jarak dua titik pada bidang Kartesius merupakan aplikasi dari teorema Pythagoras.
24. Tentukan jarak antara titik $(1, 2, 3)$ dan titik $(4, 6, 3)$ di ruang tiga dimensi.
25. Dua titik $A(p, 2)$ dan $B(6, q)$ memiliki titik tengah $M(3, 5)$. Hitung jarak $AB$.



# BAB 3 VEKTOR DALAM RUANG TIGA DIMENSI

## 3.1 Pengertian dan Notasi Vektor

Dalam matematika dan fisika, terdapat dua jenis besaran utama:
1. **Besaran Skalar:** Besaran yang hanya memiliki nilai (magnitudo). 
   * *Contoh:* panjang, massa, suhu, waktu, dan volume.
2. **Besaran Vektor:** Besaran yang memiliki nilai (magnitudo) dan arah. 
   * *Contoh:* kecepatan, percepatan, gaya, momentum, dan perpindahan.

Secara geometris, vektor digambarkan sebagai **ruas garis berarah (anak panah)** di mana:
* **Panjang anak panah** merepresentasikan magnitudo (nilai).
* **Arah anak panah** merepresentasikan arah vektor tersebut.
* **Titik pangkal** disebut titik awal (*initial point*).
* **Titik ujung** disebut titik akhir (*terminal point*).

### Notasi Vektor
Beberapa notasi vektor yang umum digunakan antara lain:
* Huruf kecil dicetak tebal: $\mathbf{a}$, $\mathbf{b}$, $\mathbf{v}$, dll.
* Huruf dengan tanda panah di atasnya: $\vec{a}$, $\vec{b}$, $\vec{v}$, dll.
* Untuk vektor dengan titik awal $A$ his dan titik akhir $B$, digunakan notasi $\vec{AB}$ atau $\mathbf{AB}$.

### Jenis-Jenis Vektor Khusus

#### 1. Vektor Sama
Dua vektor dikatakan sama apabila keduanya memiliki **magnitudo yang sama dan arah yang sama**, terlepas dari letak titik awalnya. Dengan demikian, sebuah vektor dapat dipindahkan secara paralel tanpa mengubah identitasnya. Vektor seperti ini disebut **vektor bebas** (*free vector*).

#### 2. Vektor Negatif
Vektor negatif dari suatu vektor $\mathbf{v}$, dilambangkan dengan $-\mathbf{v}$, adalah vektor yang memiliki magnitudo sama dengan $\mathbf{v}$ tetapi **arahnya berlawanan**.

#### 3. Vektor Nol
Vektor nol, dilambangkan dengan $\mathbf{0}$, adalah vektor yang **magnitudonya nol**. Arah vektor nol tidak terdefinisi (atau dapat dianggap sebarang). Vektor nol berperan sebagai elemen identitas dalam operasi penjumlahan vektor.

---

### Contoh 3.1
Misalkan titik $A(1, 2, 3)$, $B(4, 5, 6)$, $C(7, 8, 9)$, dan $D(10, 11, 12)$. Tunjukkan bahwa $\vec{AB} = \vec{CD}$!

**Penyelesaian:**
$$\vec{AB} = B - A = (4-1, 5-2, 6-3) = (3, 3, 3)$$
$$\vec{CD} = D - C = (10-7, 11-8, 12-9) = (3, 3, 3)$$

Karena komponen-komponennya identik, maka $\vec{AB} = \vec{CD}$. Kedua vektor tersebut memiliki magnitudo dan arah yang sama, meskipun titik awal dan titik akhirnya berbeda.

---

## 3.2 Vektor dalam Sistem Koordinat
Apabila titik awal suatu vektor diletakkan di titik asal $O(0, 0, 0)$ dan titik akhirnya berada di titik $P(x, y, z)$, maka vektor tersebut dinamakan **vektor posisi** titik $P$, dilambangkan dengan $\vec{OP}$ atau $\mathbf{r}$. Dalam hal ini, vektor posisi tersebut secara unik diwakili oleh tripel terurut $(x, y, z)$, dan koordinat titik $P$ pada sistem Kartesius sama dengan komponen-komponen vektor posisinya.



Setiap vektor di ruang tiga dimensi dapat dinyatakan sebagai tripel terurut komponen-komponennya. Misalkan vektor $\mathbf{v}$ memiliki titik awal $A(a_1, a_2, a_3)$ dan titik akhir $B(b_1, b_2, b_3)$, maka komponen-komponen vektor $\mathbf{v}$ adalah:

$$\mathbf{v} = \vec{AB} = (b_1 - a_1, b_2 - a_2, b_3 - a_3)$$

Notasi vektor dalam bentuk komponen yang umum digunakan adalah:
* $\mathbf{v} = \langle v_1, v_2, v_3 \rangle$ (notasi tanda kurung siku miring)
* $\mathbf{v} = (v_1, v_2, v_3)$ (notasi tanda kurung biasa)

### Magnitudo (Besar) Vektor
Besar atau magnitudo vektor $\mathbf{v} = (v_1, v_2, v_3)$ dihitung dengan rumus jarak yang merupakan analog dari teorema Pythagoras:

$$|\mathbf{v}| = \sqrt{v_1^2 + v_2^2 + v_3^2}$$

Magnitudo selalu non-negatif dan $|\mathbf{v}| = 0$ jika dan hanya jika $\mathbf{v}$ adalah vektor nol.

---

### Contoh 3.2
Diberikan titik $A(2, -1, 4)$ dan $B(5, 3, -2)$. Tentukan vektor $\vec{AB}$ dan magnitudonya.

**Penyelesaian:**
$$\vec{AB} = B - A = (5-2, 3-(-1), -2-4) = (3, 4, -6)$$
$$|\vec{AB}| = \sqrt{3^2 + 4^2 + (-6)^2} = \sqrt{9 + 16 + 36} = \sqrt{61} \approx 7{,}81$$

### Contoh 3.3
Tentukan komponen-komponen vektor $\mathbf{v}$ yang memiliki magnitudo $7$ dan kosinus arah $\left(\frac{3}{7}, -\frac{2}{7}, \frac{6}{7}\right)$.

**Penyelesaian:**
$$\mathbf{v} = |\mathbf{v}| \times (l, m, n) = 7 \times \left(\frac{3}{7}, -\frac{2}{7}, \frac{6}{7}\right) = (3, -2, 6)$$

**Verifikasi:** |v| = √(9 + 4 + 36) = √49 = 7. ✓

---

## 3.3 Operasi Aljabar Vektor
Vektor dapat dioperasikan secara aljabar mirip dengan bilangan, namun dengan aturan tersendiri yang menggambarkan sifat geometrisnya. Operasi dasar pada vektor meliputi penjumlahan, pengurangan, dan perkalian vektor dengan skalar.

### Penjumlahan Vektor
Misalkan $\mathbf{a} = (a_1, a_2, a_3)$ dan $\mathbf{b} = (b_1, b_2, b_3)$. Jumlah dari kedua vektor tersebut didefinisikan sebagai vektor yang komponen-komponennya merupakan jumlah komponen yang bersesuaian:

$$\mathbf{a} + \mathbf{b} = (a_1 + b_1, a_2 + b_2, a_3 + b_3)$$

Secara geometris, penjumlahan vektor dapat dilakukan dengan dua cara:
1. **Aturan Segitiga (atau aturan poligon):** Vektor kedua diletakkan dengan titik awalnya berimpit dengan titik akhir vektor pertama; resultan adalah vektor dari titik awal vektor pertama ke titik akhir vektor kedua.
2. **Aturan Jajaran Genjang:** Kedua vektor diletakkan dengan titik awal yang sama, dan resultan adalah diagonal jajaran genjang dari titik awal yang sama tersebut.

### Pengurangan Vektor
Pengurangan dua vektor didefinisikan sebagai:

$$\mathbf{a} - \mathbf{b} = \mathbf{a} + (-\mathbf{b}) = (a_1 - b_1, a_2 - b_2, a_3 - b_3)$$

Secara geometris, vektor $\mathbf{a} - \mathbf{b}$ dapat diperoleh dengan meletakkan kedua vektor $\mathbf{a}$ dan $\mathbf{b}$ berpangkal di titik yang sama; maka $\mathbf{a} - \mathbf{b}$ adalah vektor yang menghubungkan titik akhir $\mathbf{b}$ ke titik akhir $\mathbf{a}$.

### Perkalian Vektor dengan Skalar
Misalkan $k$ adalah bilangan real (skalar) dan $\mathbf{a} = (a_1, a_2, a_3)$. Perkalian skalar $k$ dengan vektor $\mathbf{a}$ didefinisikan sebagai:

$$k \cdot \mathbf{a} = (ka_1, ka_2, ka_3)$$

Magnitudo dari $k \cdot \mathbf{a}$ adalah $|k| \cdot |\mathbf{a}|$, dan arahnya:
* **Sama** dengan $\mathbf{a}$ jika $k > 0$.
* **Berlawanan arah** dengan $\mathbf{a}$ jika $k < 0$.
* Jika $k = 0$, maka $k \cdot \mathbf{a} = \mathbf{0}$ (vektor nol).

---

### Sifat-Sifat Operasi Vektor
Operasi penjumlahan vektor dan perkalian skalar memenuhi sifat-sifat berikut, untuk sebarang vektor $\mathbf{a}, \mathbf{b}, \mathbf{c}$ dan skalar $k, m$:

1. **Komutatif:** $\mathbf{a} + \mathbf{b} = \mathbf{b} + \mathbf{a}$
2. **Asosiatif:** $(\mathbf{a} + \mathbf{b}) + \mathbf{c} = \mathbf{a} + (\mathbf{b} + \mathbf{c})$
3. **Identitas:** $\mathbf{a} + \mathbf{0} = \mathbf{a}$
4. **Invers:** $\mathbf{a} + (-\mathbf{a}) = \mathbf{0}$
5. **Distributif:** $k(\mathbf{a} + \mathbf{b}) = k\mathbf{a} + k\mathbf{b}$
6. **Distributif:** $(k + m)\mathbf{a} = k\mathbf{a} + m\mathbf{a}$
7. **Asosiatif Skalar:** $k(m\mathbf{a}) = (km)\mathbf{a}$
8. **Identitas Skalar:** $1 \cdot \mathbf{a} = \mathbf{a}$

Himpunan semua vektor di ruang tiga dimensi dengan operasi penjumlahan dan perkalian dengan skalar membentuk struktur aljabar yang disebut **ruang vektor**.

---

### Contoh 3.4
Diberikan vektor $\mathbf{a} = (2, -3, 4)$ dan $\mathbf{b} = (1, 5, -2)$. Tentukan:
a) $\mathbf{a} + \mathbf{b}$
b) $\mathbf{a} - \mathbf{b}$
c) $3\mathbf{a} - 2\mathbf{b}$
d) $|2\mathbf{a} + 3\mathbf{b}|$

**Penyelesaian:**
* **a)** $\mathbf{a} + \mathbf{b} = (2+1, -3+5, 4+(-2)) = (3, 2, 2)$
* **b)** $\mathbf{a} - \mathbf{b} = (2-1, -3-5, 4-(-2)) = (1, -8, 6)$
* **c)** $3\mathbf{a} = (6, -9, 12)$ dan $2\mathbf{b} = (2, 10, -4)$
  $$3\mathbf{a} - 2\mathbf{b} = (6-2, -9-10, 12-(-4)) = (4, -19, 16)$$
* **d)** $2\mathbf{a} = (4, -6, 8)$ dan $3\mathbf{b} = (3, 15, -6)$
  $$2\mathbf{a} + 3\mathbf{b} = (7, 9, 2)$$
  $$|2\mathbf{a} + 3\mathbf{b}| = \sqrt{7^2 + 9^2 + 2^2} = \sqrt{49 + 81 + 4} = \sqrt{134} \approx 11{,}58$$

### Contoh 3.5
Tentukan nilai $k$ sehingga vektor $(k, 2, 3)$ dan vektor $(4, k-1, 6)$ sejajar.

**Penyelesaian:**
Dua vektor sejajar jika komponen-komponennya sebanding:

$$\frac{k}{4} = \frac{2}{k-1} = \frac{3}{6} = \frac{1}{2}$$

* Dari $\frac{k}{4} = \frac{1}{2}$, diperoleh $k = 2$.
  * *Verifikasi:* $\frac{2}{k-1} = \frac{2}{2-1} = 2 \neq \frac{1}{2}$ (Ini berarti $k = 2$ tidak konsisten).
* Coba dari $\frac{2}{k-1} = \frac{1}{2}$, diperoleh $k - 1 = 4 \implies k = 5$.
  * *Verifikasi:* $\frac{k}{4} = \frac{5}{4} \neq \frac{1}{2}$ (Tidak konsisten).

Berarti tidak ada nilai $k$ yang membuat kedua vektor sejajar dengan tepat sebanding $1:2$.

**Alternatif:** kita gunakan syarat sebanding dengan parameter $t$, yaitu $(k, 2, 3) = t(4, k-1, 6)$.
* Dari komponen ketiga: $3 = 6t \implies t = \frac{1}{2}$.
* Komponen pertama: $k = 4t = 2$.
* Komponen kedua: $2 = t(k-1) \implies 2 = \frac{1}{2}(2-1) \implies 2 = \frac{1}{2}$ (Tidak konsisten).

**Kesimpulan:** Jadi memang tidak ada nilai $k$ yang memenuhi syarat kesejajaran kedua vektor.

## 3.4 Vektor Posisi dan Vektor Satuan

Sebagaimana telah disebutkan, vektor posisi suatu titik $P(x, y, z)$ adalah vektor dari titik asal $O$ ke titik $P$, yaitu $\vec{OP} = (x, y, z)$. Vektor posisi sangat berguna untuk merepresentasikan lokasi titik dalam suatu sistem koordinat dan untuk menurunkan banyak rumus geometri.

Beberapa sifat vektor posisi yang penting:
* **Vektor yang menghubungkan dua titik $A$ dan $B$** adalah selisih vektor posisinya: 
    $$\vec{AB} = \vec{OB} - \vec{OA} = \mathbf{b} - \mathbf{a}$$
    (dengan $\mathbf{a}$ dan $\mathbf{b}$ masing-masing vektor posisi $A$ dan $B$).
* **Jika $M$ adalah titik tengah $AB$**, maka vektor posisi $M$ adalah:
    $$\frac{\mathbf{a} + \mathbf{b}}{2}$$
* **Jika titik $R$ membagi $AB$ dengan perbandingan $m : n$** (internal), maka vektor posisi $R$ adalah:
    $$\frac{n\mathbf{a} + m\mathbf{b}}{m+n}$$

### Vektor Satuan
Vektor satuan adalah vektor yang magnitudonya sama dengan 1. Vektor satuan biasanya dinotasikan dengan topi (*caret*), misalnya $\hat{v}$ atau $\hat{e}$.

Setiap vektor $\mathbf{v} \neq 0$ dapat dinormalisasi menjadi vektor satuan yang searah dengan $\mathbf{v}$, yaitu:
$$\hat{v} = \frac{\mathbf{v}}{|\mathbf{v}|}$$

Vektor satuan $\hat{v}$ ini disebut vektor satuan dalam arah $\mathbf{v}$. Komponen-komponen dari $\hat{v}$ tepat sama dengan kosinus arah garis yang membentang sepanjang vektor $\mathbf{v}$.

---

> **Contoh 3.6**
> Tentukan vektor satuan yang searah dengan vektor $\mathbf{v} = (4, -3, 12)$.
> 
> **Penyelesaian:**
> * $|\mathbf{v}| = \sqrt{16 + 9 + 144} = \sqrt{169} = 13$
> * $\hat{v} = \frac{\mathbf{v}}{|\mathbf{v}|} = \left(\frac{4}{13}, -\frac{3}{13}, \frac{12}{13}\right)$
> 
> **Verifikasi:** $|\hat{v}| = \sqrt{\frac{16}{169} + \frac{9}{169} + \frac{144}{169}} = \sqrt{\frac{169}{169}} = 1$  ✓

---

> **Contoh 3.7**
> Tentukan vektor $\mathbf{v}$ dengan magnitudo 6 yang searah dengan vektor $\mathbf{a} = (1, 2, -2)$.
> 
> **Penyelesaian:**
> * $|\mathbf{a}| = \sqrt{1 + 4 + 4} = \sqrt{9} = 3$
> * Vektor satuan $\hat{a} = \left(\frac{1}{3}, \frac{2}{3}, -\frac{2}{3}\right)$
> * $\mathbf{v} = |\mathbf{v}| \cdot \hat{a} = 6 \cdot \left(\frac{1}{3}, \frac{2}{3}, -\frac{2}{3}\right) = (2, 4, -4)$
> 
> **Verifikasi:** $|\mathbf{v}| = \sqrt{4 + 16 + 16} = \sqrt{36} = 6$ ✓

---

## 3.5 Vektor Basis $\mathbf{i}, \mathbf{j}, \mathbf{k}$

Dalam sistem koordinat Kartesius tiga dimensi, terdapat tiga vektor satuan istimewa yang masing-masing searah dengan sumbu-X positif, sumbu-Y positif, dan sumbu-Z positif. Ketiga vektor satuan ini disebut vektor basis standar atau vektor satuan standar, dan biasanya dinotasikan dengan $\mathbf{i}$, $\mathbf{j}$, dan $\mathbf{k}$:
$$\mathbf{i} = (1, 0, 0), \quad \mathbf{j} = (0, 1, 0), \quad \mathbf{k} = (0, 0, 1)$$

Setiap vektor $\mathbf{v} = (v_1, v_2, v_3)$ di ruang tiga dimensi dapat dinyatakan secara unik sebagai kombinasi linear dari vektor-vektor basis $\mathbf{i}, \mathbf{j}, \mathbf{k}$:
$$\mathbf{v} = v_1\mathbf{i} + v_2\mathbf{j} + v_3\mathbf{k}$$

Bilangan $v_1, v_2, v_3$ disebut komponen-komponen vektor $\mathbf{v}$ terhadap basis standar. Notasi ini sering disebut sebagai notasi $\mathbf{i}$-$\mathbf{j}$-$\mathbf{k}$, dan setara dengan notasi tripel $(v_1, v_2, v_3)$.

Beberapa sifat vektor basis:
* $|\mathbf{i}| = |\mathbf{j}| = |\mathbf{k}| = 1$ (vektor satuan).
* $\mathbf{i} \cdot \mathbf{j} = \mathbf{j} \cdot \mathbf{k} = \mathbf{k} \cdot \mathbf{i} = 0$ (saling tegak lurus).
* $\mathbf{i} \times \mathbf{j} = \mathbf{k}, \quad \mathbf{j} \times \mathbf{k} = \mathbf{i}, \quad \mathbf{k} \times \mathbf{i} = \mathbf{j}$ (hasil kali silang akan dibahas pada subbab 3.7).

---

> **Contoh 3.8**

Diberikan vektor $\mathbf{a} = 2\mathbf{i} - 3\mathbf{j} + 5\mathbf{k}$ dan $\mathbf{b} = \mathbf{i} + 4\mathbf{j} - 2\mathbf{k}$. Tentukan:
* a) $\mathbf{a} + \mathbf{b}$
* b) $\mathbf{a} - \mathbf{b}$
* c) $3\mathbf{a} - 2\mathbf{b}$
* d) $|\mathbf{a} + \mathbf{b}|$

**Penyelesaian:**

* **a)** $\mathbf{a} + \mathbf{b} = (2+1)\mathbf{i} + (-3+4)\mathbf{j} + (5+(-2))\mathbf{k} = 3\mathbf{i} + \mathbf{j} + 3\mathbf{k}$
* **b)** $\mathbf{a} - \mathbf{b} = (2-1)\mathbf{i} + (-3-4)\mathbf{j} + (5-(-2))\mathbf{k} = \mathbf{i} - 7\mathbf{j} + 7\mathbf{k}$
* **c)** Tentukan komponen skalar terlebih dahulu:
  $$3\mathbf{a} = 6\mathbf{i} - 9\mathbf{j} + 15\mathbf{k}$$
  $$2\mathbf{b} = 2\mathbf{i} + 8\mathbf{j} - 4\mathbf{k}$$
  Maka:
  $$3\mathbf{a} - 2\mathbf{b} = (6-2)\mathbf{i} + (-9-8)\mathbf{j} + (15-(-4))\mathbf{k} = 4\mathbf{i} - 17\mathbf{j} + 19\mathbf{k}$$
* **d)** Diketahui dari poin (a) bahwa $\mathbf{a} + \mathbf{b} = 3\mathbf{i} + \mathbf{j} + 3\mathbf{k}$, maka magnitudonya adalah:
  $$|\mathbf{a} + \mathbf{b}| = \sqrt{3^2 + 1^2 + 3^2} = \sqrt{9 + 1 + 9} = \sqrt{19} \approx 4,36$$
---

### Contoh 3.9

Sebuah vektor $\mathbf{v}$ memiliki magnitudo $10$ dan membentuk sudut $60^\circ$ dengan sumbu-$X$, $120^\circ$ dengan sumbu-$Y$, dan sudut akut $\gamma$ dengan sumbu-$Z$. Tentukan komponen-komponen vektor $\mathbf{v}$ dalam notasi $\mathbf{i}$, $\mathbf{j}$, $\mathbf{k}$.

#### *Penyelesaian:*

Kosinus arah: $l = \cos 60^\circ = 1/2$, $m = \cos 120^\circ = -1/2$.

Gunakan $l^2 + m^2 + n^2 = 1$: $(1/2)^2 + (-1/2)^2 + n^2 = 1 \rightarrow 1/4 + 1/4 + n^2 = 1 \rightarrow n^2 = 1/2 \rightarrow n = \sqrt{2}/2$ (karena $\gamma$ akut).

$$v_1 = |\mathbf{v}| \cdot l = 10 \cdot (1/2) = 5$$
$$v_2 = |\mathbf{v}| \cdot m = 10 \cdot (-1/2) = -5$$
$$v_3 = |\mathbf{v}| \cdot n = 10 \cdot (\sqrt{2}/2) = 5\sqrt{2}$$

Jadi, $\mathbf{v} = 5\mathbf{i} - 5\mathbf{j} + 5\sqrt{2}\mathbf{k}$.

---

**Verifikasi:**
$$|\mathbf{v}| = \sqrt{3^2 + (-2)^2 + 6^2} = \sqrt{9 + 4 + 36} = \sqrt{49} = 7 \quad \text{}$$ 

---

## 3.6 Hasil Kali Skalar (*Dot Product*)

Salah satu operasi penting pada vektor adalah hasil kali skalar atau *dot product*, yang juga dikenal sebagai hasil kali titik atau hasil kali dalam (*inner product*). Hasil kali skalar dari dua vektor menghasilkan suatu bilangan skalar (bukan vektor).

### Definisi Hasil Kali Skalar
Hasil kali skalar dari dua vektor $\mathbf{a} = (a_1, a_2, a_3)$ dan $\mathbf{b} = (b_1, b_2, b_3)$ didefinisikan sebagai:
$$\mathbf{a} \cdot \mathbf{b} = a_1b_1 + a_2b_2 + a_3b_3$$

Definisi alternatif yang setara secara geometris adalah:
$$\mathbf{a} \cdot \mathbf{b} = |\mathbf{a}| \cdot |\mathbf{b}| \cdot \cos \theta$$
dengan $\theta$ adalah sudut antara vektor $\mathbf{a}$ dan $\mathbf{b}$, di mana $0 \le \theta \le \pi$.

### Sifat-Sifat Hasil Kali Skalar
Untuk sebarang vektor $\mathbf{a}, \mathbf{b}, \mathbf{c}$ dan skalar $k$:
1.  **Komutatif:** $\mathbf{a} \cdot \mathbf{b} = \mathbf{b} \cdot \mathbf{a}$
2.  **Distributif:** $\mathbf{a} \cdot (\mathbf{b} + \mathbf{c}) = \mathbf{a} \cdot \mathbf{b} + \mathbf{a} \cdot \mathbf{c}$
3.  **Asosiatif terhadap skalar:** $(k\mathbf{a}) \cdot \mathbf{b} = k(\mathbf{a} \cdot \mathbf{b}) = \mathbf{a} \cdot (k\mathbf{b})$
4.  **Hasil kali dengan diri sendiri:** $\mathbf{a} \cdot \mathbf{a} = |\mathbf{a}|^2 \ge 0$
5.  $\mathbf{a} \cdot \mathbf{a} = 0$ jika dan hanya jika $\mathbf{a} = \mathbf{0}$

### Penerapan Hasil Kali Skalar
1.  **Menentukan sudut antara dua vektor:**
    $$\cos \theta = \frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{a}| \cdot |\mathbf{b}|}$$
2.  **Menentukan apakah dua vektor saling tegak lurus:** Dua vektor tak nol $\mathbf{a}$ dan $\mathbf{b}$ saling tegak lurus jika dan hanya jika $\mathbf{a} \cdot \mathbf{b} = 0$.
3.  **Proyeksi vektor:**
    * Proyeksi skalar (panjang proyeksi) vektor $\mathbf{a}$ pada vektor $\mathbf{b}$:
        $$\text{comp}_{\mathbf{b}}\mathbf{a} = \frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{b}|}$$
    * Proyeksi vektor $\mathbf{a}$ pada vektor $\mathbf{b}$:
        $$\text{proj}_{\mathbf{b}}\mathbf{a} = \left[\frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{b}|^2}\right] \cdot \mathbf{b}$$
4.  **Magnitudo vektor:** $|\mathbf{a}| = \sqrt{\mathbf{a} \cdot \mathbf{a}}$

---

> **Contoh 3.10**
> Hitung $\mathbf{a} \cdot \mathbf{b}$ jika $\mathbf{a} = 2\mathbf{i} + 3\mathbf{j} - \mathbf{k}$ dan $\mathbf{b} = \mathbf{i} - 2\mathbf{j} + 4\mathbf{k}$.
> 
> **Penyelesaian:**
> $\mathbf{a} \cdot \mathbf{b} = (2)(1) + (3)(-2) + (-1)(4) = 2 - 6 - 4 = -8$

---

> **Contoh 3.11**
> Tentukan sudut antara vektor $\mathbf{a} = (1, 2, 2)$ dan $\mathbf{b} = (3, 0, -4)$.
> 
> **Penyelesaian:**
> * $\mathbf{a} \cdot \mathbf{b} = (1)(3) + (2)(0) + (2)(-4) = 3 + 0 - 8 = -5$
> * $|\mathbf{a}| = \sqrt{1 + 4 + 4} = \sqrt{9} = 3$
> * $|\mathbf{b}| = \sqrt{9 + 0 + 16} = \sqrt{25} = 5$
> * $\cos \theta = \frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{a}| \cdot |\mathbf{b}|} = \frac{-5}{3 \cdot 5} = -\frac{1}{3}$
> * $\theta = \arccos(-1/3) \approx 109,47^\circ$

---

> **Contoh 3.12**
> Tunjukkan bahwa vektor $\mathbf{a} = (2, -1, 3)$ dan $\mathbf{b} = (1, 5, 1)$ saling tegak lurus.
> 
> **Penyelesaian:**
> $\mathbf{a} \cdot \mathbf{b} = (2)(1) + (-1)(5) + (3)(1) = 2 - 5 + 3 = 0$
> Karena $\mathbf{a} \cdot \mathbf{b} = 0$, kedua vektor terbukti saling tegak lurus.

---

> **Contoh 3.13**
> Tentukan proyeksi vektor $\mathbf{a} = (3, 4, 5)$ pada vektor $\mathbf{b} = (1, 0, 1)$.
> 
> **Penyelesaian:**
> * $\mathbf{a} \cdot \mathbf{b} = (3)(1) + (4)(0) + (5)(1) = 3 + 5 = 8$
> * $|\mathbf{b}|^2 = 1 + 0 + 1 = 2$
> * $\text{proj}_{\mathbf{b}}\mathbf{a} = \frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{b}|^2} \cdot \mathbf{b} = \frac{8}{2} \cdot (1, 0, 1) = 4(1, 0, 1) = (4, 0, 4)$
> * Proyeksi skalar: $\text{comp}_{\mathbf{b}}\mathbf{a} = \frac{\mathbf{a} \cdot \mathbf{b}}{|\mathbf{b}|} = \frac{8}{\sqrt{2}} = 4\sqrt{2}$

---

> **Contoh 3.14**
> Tentukan nilai $k$ agar vektor $\mathbf{a} = (k, -2, 5)$ dan $\mathbf{b} = (3, k, -1)$ saling tegak lurus.
> 
> **Penyelesaian:**
> Syarat tegak lurus: $\mathbf{a} \cdot \mathbf{b} = 0$
> $$(k)(3) + (-2)(k) + (5)(-1) = 0 \implies 3k - 2k - 5 = 0 \implies k = 5$$
> Jadi, nilai $k$ yang membuat $\mathbf{a}$ dan $\mathbf{b}$ tegak lurus adalah $k = 5$.

---

## 3.7 Hasil Kali Vektor (*Cross Product*)

Hasil kali vektor atau *cross product* (juga disebut hasil kali silang) merupakan operasi yang khas pada ruang tiga dimensi. Berbeda dengan *dot product*, *cross product* dari dua vektor menghasilkan vektor baru yang tegak lurus terhadap kedua vektor asalnya.

### Definisi Hasil Kali Vektor
Hasil kali vektor dari $\mathbf{a} = (a_1, a_2, a_3)$ dan $\mathbf{b} = (b_1, b_2, b_3)$ didefinisikan melalui bentuk determinan formal berikut:
$$\mathbf{a} \times \mathbf{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ a_1 & a_2 & a_3 \\ b_1 & b_2 & b_3 \end{vmatrix}$$

Determinan ini dapat diperluas menggunakan ekspansi baris pertama menjadi:
$$\mathbf{a} \times \mathbf{b} = (a_2b_3 - a_3b_2)\mathbf{i} - (a_1b_3 - a_3b_1)\mathbf{j} + (a_1b_2 - a_2b_1)\mathbf{k}$$
Atau secara komponen:
$$\mathbf{a} \times \mathbf{b} = (a_2b_3 - a_3b_2, \, a_3b_1 - a_1b_3, \, a_1b_2 - a_2b_1)$$

### Sifat Geometris Hasil Kali Vektor
Vektor $\mathbf{a} \times \mathbf{b}$ memiliki sifat geometris penting berikut:
1.  **Tegak lurus:** $\mathbf{a} \times \mathbf{b}$ tegak lurus terhadap $\mathbf{a}$ dan terhadap $\mathbf{b}$.
2.  **Magnitudo:** $|\mathbf{a} \times \mathbf{b}| = |\mathbf{a}| \cdot |\mathbf{b}| \cdot \sin \theta$, dengan $\theta$ adalah sudut antara $\mathbf{a}$ dan $\mathbf{b}$ ($0 \le \theta \le \pi$).
3.  **Arah:** Mengikuti aturan tangan kanan (putar jari dari $\mathbf{a}$ ke $\mathbf{b}$, maka ibu jari menunjuk arah $\mathbf{a} \times \mathbf{b}$).
4.  Magnitudo $|\mathbf{a} \times \mathbf{b}|$ sama dengan **luas jajaran genjang** yang dibentuk oleh $\mathbf{a}$ dan $\mathbf{b}$.

### Sifat-Sifat Aljabar Hasil Kali Vektor
Untuk sebarang vektor $\mathbf{a}, \mathbf{b}, \mathbf{c}$ dan skalar $k$:
1.  **Antikomutatif:** $\mathbf{a} \times \mathbf{b} = -(\mathbf{b} \times \mathbf{a})$
2.  **Distributif:** $\mathbf{a} \times (\mathbf{b} + \mathbf{c}) = \mathbf{a} \times \mathbf{b} + \mathbf{a} \times \mathbf{c}$
3.  **Asosiatif skalar:** $(k\mathbf{a}) \times \mathbf{b} = k(\mathbf{a} \times \mathbf{b}) = \mathbf{a} \times (k\mathbf{b})$
4.  **Identitas khusus:** $\mathbf{a} \times \mathbf{a} = \mathbf{0}$
5.  Jika $\mathbf{a}$ dan $\mathbf{b}$ sejajar, maka $\mathbf{a} \times \mathbf{b} = \mathbf{0}$.

> *Catatan:* Hasil kali vektor **tidak** asosiatif secara umum: $(\mathbf{a} \times \mathbf{b}) \times \mathbf{c} \neq \mathbf{a} \times (\mathbf{b} \times \mathbf{c})$.

### Hasil Kali Vektor Basis Standar
Vektor-vektor basis $\mathbf{i}, \mathbf{j}, \mathbf{k}$ memenuhi hubungan siklik:
$$\mathbf{i} \times \mathbf{j} = \mathbf{k}, \quad \mathbf{j} \times \mathbf{k} = \mathbf{i}, \quad \mathbf{k} \times \mathbf{i} = \mathbf{j}$$
$$\mathbf{j} \times \mathbf{i} = -\mathbf{k}, \quad \mathbf{k} \times \mathbf{j} = -\mathbf{i}, \quad \mathbf{i} \times \mathbf{k} = -\mathbf{j}$$
$$\mathbf{i} \times \mathbf{i} = \mathbf{j} \times \mathbf{j} = \mathbf{k} \times \mathbf{k} = \mathbf{0}$$

---

> **Contoh 3.15**
> Hitung $\mathbf{a} \times \mathbf{b}$ jika $\mathbf{a} = (1, 2, 3)$ dan $\mathbf{b} = (4, 5, 6)$.
> 
> **Penyelesaian:**
> $$\mathbf{a} \times \mathbf{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 1 & 2 & 3 \\ 4 & 5 & 6 \end{vmatrix}$$
> $$= \mathbf{i}(2\cdot6 - 3\cdot5) - \mathbf{j}(1\cdot6 - 3\cdot4) + \mathbf{k}(1\cdot5 - 2\cdot4)$$
> $$= \mathbf{i}(12 - 15) - \mathbf{j}(6 - 12) + \mathbf{k}(5 - 8) = -3\mathbf{i} + 6\mathbf{j} - 3\mathbf{k} = (-3, 6, -3)$$
> 
> **Verifikasi:** > * $(\mathbf{a} \times \mathbf{b}) \cdot \mathbf{a} = (-3)(1) + (6)(2) + (-3)(3) = -3 + 12 - 9 = 0$ ✓
> * $(\mathbf{a} \times \mathbf{b}) \cdot \mathbf{b} = (-3)(4) + (6)(5) + (-3)(6) = -12 + 30 - 18 = 0$ ✓

---

> **Contoh 3.16**
> Tentukan luas jajaran genjang yang dibentuk oleh vektor $\mathbf{u} = (1, 2, 0)$ dan $\mathbf{v} = (3, 0, 4)$.
> 
> **Penyelesaian:**
> $$\mathbf{u} \times \mathbf{v} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 1 & 2 & 0 \\ 3 & 0 & 4 \end{vmatrix} = \mathbf{i}(8 - 0) - \mathbf{j}(4 - 0) + \mathbf{k}(0 - 6) = (8, -4, -6)$$
> $$\text{Luas} = |\mathbf{u} \times \mathbf{v}| = \sqrt{64 + 16 + 36} = \sqrt{116} = 2\sqrt{29} \approx 10,77 \text{ satuan luas}$$

---

> **Contoh 3.17**
> Tentukan luas segitiga dengan titik-titik sudut $A(1, 0, 0)$, $B(0, 2, 0)$, $C(0, 0, 3)$.
> 
> **Penyelesaian:**
> * $\vec{AB} = B - A = (-1, 2, 0)$
> * $\vec{AC} = C - A = (-1, 0, 3)$
> 
> $$\vec{AB} \times \vec{AC} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ -1 & 2 & 0 \\ -1 & 0 & 3 \end{vmatrix} = \mathbf{i}(6 - 0) - \mathbf{j}(-3 - 0) + \mathbf{k}(0 - (-2)) = (6, 3, 2)$$
> * $|\vec{AB} \times \vec{AC}| = \sqrt{36 + 9 + 4} = \sqrt{49} = 7$
> * $\text{Luas segitiga} = \frac{1}{2} \cdot |\vec{AB} \times \vec{AC}| = \frac{7}{2} = 3,5 \text{ satuan luas}$

---

> **Contoh 3.18**
> Tentukan vektor satuan yang tegak lurus terhadap $\mathbf{a} = (2, -1, 1)$ dan $\mathbf{b} = (3, 4, -1)$.
> 
> **Penyelesaian:**
> Hitung $\mathbf{a} \times \mathbf{b}$:
> $$\mathbf{a} \times \mathbf{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & -1 & 1 \\ 3 & 4 & -1 \end{vmatrix} = \mathbf{i}(1 - 4) - \mathbf{j}(-2 - 3) + \mathbf{k}(8 + 3) = (-3, 5, 11)$$
> * $|\mathbf{a} \times \mathbf{b}| = \sqrt{9 + 25 + 121} = \sqrt{155}$
> * Vektor satuan: $\hat{n} = \frac{1}{\sqrt{155}} \cdot (-3, 5, 11) = \left(-\frac{3}{\sqrt{155}}, \frac{5}{\sqrt{155}}, \frac{11}{\sqrt{155}}\right)$

---

## 3.8 Hasil Kali Tripel Skalar

Hasil kali tripel skalar (*scalar triple product*) adalah operasi yang melibatkan tiga vektor dan menghasilkan nilai skalar. Hasil kali tripel skalar dari $\mathbf{a}, \mathbf{b}, \mathbf{c}$ didefinisikan sebagai:
$$[\mathbf{a}, \mathbf{b}, \mathbf{c}] = \mathbf{a} \cdot (\mathbf{b} \times \mathbf{c})$$

Dapat dihitung dengan determinan matriks $3 \times 3$:
$$[\mathbf{a}, \mathbf{b}, \mathbf{c}] = \begin{vmatrix} a_1 & a_2 & a_3 \\ b_1 & b_2 & b_3 \\ c_1 & c_2 & c_3 \end{vmatrix}$$

### Sifat-Sifat Hasil Kali Tripel Skalar
1.  **Permutasi siklik:** $[\mathbf{a}, \mathbf{b}, \mathbf{c}] = [\mathbf{b}, \mathbf{c}, \mathbf{a}] = [\mathbf{c}, \mathbf{a}, \mathbf{b}]$
2.  **Permutasi anti-siklik mengubah tanda:** $[\mathbf{a}, \mathbf{c}, \mathbf{b}] = -[\mathbf{a}, \mathbf{b}, \mathbf{c}]$
3.  **Pergeseran titik dan silang:** $\mathbf{a} \cdot (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \times \mathbf{b}) \cdot \mathbf{c}$
4.  Jika satu vektor merupakan kombinasi linear dari dua yang lain, maka $[\mathbf{a}, \mathbf{b}, \mathbf{c}] = 0$.

### Makna Geometris
* Nilai mutlak $|[\mathbf{a}, \mathbf{b}, \mathbf{c}]|$ menyatakan **volume paralelepiped** (kotak miring):
    $$V_{\text{paralelepiped}} = |[\mathbf{a}, \mathbf{b}, \mathbf{c}]| = |\mathbf{a} \cdot (\mathbf{b} \times \mathbf{c})|$$
* **Volume tetrahedron** (limas segitiga) yang dibentuk ketiga vektor:
    $$V_{\text{tetrahedron}} = \frac{1}{6} \cdot |[\mathbf{a}, \mathbf{b}, \mathbf{c}]|$$
* Tiga vektor $\mathbf{a}, \mathbf{b}, \mathbf{c}$ dikatakan **koplanar** (sebidang) jika dan hanya jika $[\mathbf{a}, \mathbf{b}, \mathbf{c}] = 0$.

---

> **Contoh 3.19**
> Hitung hasil kali tripel skalar dari $\mathbf{a} = (1, 2, 1)$, $\mathbf{b} = (3, -1, 2)$, $\mathbf{c} = (2, 1, -1)$.
> 
> **Penyelesaian:**
> $$[\mathbf{a}, \mathbf{b}, \mathbf{c}] = \begin{vmatrix} 1 & 2 & 1 \\ 3 & -1 & 2 \\ 2 & 1 & -1 \end{vmatrix}$$
> Ekspansi pada baris pertama:
> $$= 1 \cdot \begin{vmatrix} -1 & 2 \\ 1 & -1 \end{vmatrix} - 2 \cdot \begin{vmatrix} 3 & 2 \\ 2 & -1 \end{vmatrix} + 1 \cdot \begin{vmatrix} 3 & -1 \\ 2 & 1 \end{vmatrix}$$
> $$= 1 \cdot (1 - 2) - 2 \cdot (-3 - 4) + 1 \cdot (3 + 2) = -1 - 2(-7) + 5 = 18$$

---

> **Contoh 3.20**
> Tentukan volume paralelepiped yang dibentuk oleh vektor $\mathbf{a} = (1, 1, 0)$, $\mathbf{b} = (1, 0, 1)$, dan $\mathbf{c} = (0, 1, 1)$.
> 
> **Penyelesaian:**
> $$[\mathbf{a}, \mathbf{b}, \mathbf{c}] = \begin{vmatrix} 1 & 1 & 0 \\ 1 & 0 & 1 \\ 0 & 1 & 1 \end{vmatrix} = 1 \cdot \begin{vmatrix} 0 & 1 \\ 1 & 1 \end{vmatrix} - 1 \cdot \begin{vmatrix} 1 & 1 \\ 0 & 1 \end{vmatrix} + 0$$
> $$= 1 \cdot (0 - 1) - 1 \cdot (1 - 0) = -1 - 1 = -2$$
> $$\text{Volume} = |-2| = 2 \text{ satuan kubik}$$

---

> **Contoh 3.21**
> Tunjukkan bahwa keempat titik $A(1, 2, 3)$, $B(2, 3, 5)$, $C(3, 4, 7)$, dan $D(5, 6, 11)$ koplanar (terletak pada satu bidang).
> 
> **Penyelesaian:**
> * $\vec{AB} = (1, 1, 2)$, $\vec{AC} = (2, 2, 4)$, $\vec{AD} = (4, 4, 8)$
> * Terlihat bahwa $\vec{AC} = 2 \cdot \vec{AB}$ dan $\vec{AD} = 4 \cdot \vec{AB}$ (vektor saling sebanding).
> 
> $$[\vec{AB}, \vec{AC}, \vec{AD}] = \begin{vmatrix} 1 & 1 & 2 \\ 2 & 2 & 4 \\ 4 & 4 & 8 \end{vmatrix} = 0 \quad \text{(karena baris 2 dan 3 kelipatan baris 1)}$$
> Jadi, keempat titik terbukti koplanar.

---

## 3.9 Hasil Kali Tripel Vektor

Hasil kali tripel vektor (*vector triple product*) melibatkan tiga vektor dan menghasilkan sebuah vektor baru. Bentuk umumnya adalah:
$$\mathbf{a} \times (\mathbf{b} \times \mathbf{c})$$

Operasi ini memenuhi identitas yang dikenal sebagai **"rumus BAC-CAB"**:
$$\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = (\mathbf{a} \cdot \mathbf{c})\mathbf{b} - (\mathbf{a} \cdot \mathbf{b})\mathbf{c}$$

Identitas dual untuk $(\mathbf{a} \times \mathbf{b}) \times \mathbf{c}$ adalah:
$$(\mathbf{a} \times \mathbf{b}) \times \mathbf{c} = (\mathbf{a} \cdot \mathbf{c})\mathbf{b} - (\mathbf{b} \cdot \mathbf{c})\mathbf{a}$$

---

> **Contoh 3.22**
> Diberikan $\mathbf{a} = (1, 0, 1)$, $\mathbf{b} = (0, 1, 1)$, $\mathbf{c} = (1, 1, 0)$. Hitung $\mathbf{a} \times (\mathbf{b} \times \mathbf{c})$.
> 
> **Penyelesaian:**
> * **Metode 1: Perhitungan Langsung**
>     $$\mathbf{b} \times \mathbf{c} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 0 & 1 & 1 \\ 1 & 1 & 0 \end{vmatrix} = (-1, 1, -1)$$
>     $$\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 1 & 0 & 1 \\ -1 & 1 & -1 \end{vmatrix} = (-1, 0, 1)$$
> 
> * **Metode 2: Menggunakan Rumus BAC−CAB**
>     * $\mathbf{a} \cdot \mathbf{c} = (1)(1) + (0)(1) + (1)(0) = 1$
>     * $\mathbf{a} \cdot \mathbf{b} = (1)(0) + (0)(1) + (1)(1) = 1$
>     $$\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = 1 \cdot (0, 1, 1) - 1 \cdot (1, 1, 0) = (-1, 0, 1) \quad \checkmark$$

---

## 3.10 Aplikasi Vektor dalam Geometri

### Persamaan Garis di Ruang
Sebuah garis $L$ di ruang ditentukan oleh titik $P_0(x_0, y_0, z_0)$ yang dilaluinya dan vektor arah $\mathbf{d} = (a, b, c)$ yang sejajar garis tersebut.
* **Persamaan Vektor:** $\mathbf{r} = \mathbf{r}_0 + t\mathbf{d}, \quad t \in \mathbb{R}$
* **Persamaan Parametrik:** $x = x_0 + at, \quad y = y_0 + bt, \quad z = z_0 + ct$
* **Persamaan Simetri (jika $a,b,c \neq 0$):** $$\frac{x - x_0}{a} = \frac{y - y_0}{b} = \frac{z - z_0}{c}$$

### Persamaan Bidang
Sebuah bidang ditentukan oleh titik $P_0(x_0, y_0, z_0)$ pada bidang dan vektor normal $\mathbf{n} = (A, B, C)$ yang tegak lurus bidang.
* **Persamaan Vektor:** $\mathbf{n} \cdot (\mathbf{r} - \mathbf{r}_0) = 0$
* **Persamaan Kartesius:** $A(x - x_0) + B(y - y_0) + C(z - z_0) = 0$
* **Bentuk Umum:** $Ax + By + Cz + D = 0$ dengan $D = -(Ax_0 + By_0 + Cz_0)$.

---

> **Contoh 3.23**
> Tentukan persamaan garis yang melalui titik $(1, -2, 3)$ dan sejajar dengan vektor $(2, 1, -1)$.
> 
> **Penyelesaian:**
> * Persamaan vektor: $\mathbf{r} = (1, -2, 3) + t(2, 1, -1)$
> * Persamaan parametrik: $x = 1 + 2t, \quad y = -2 + t, \quad z = 3 - t$
> * Persamaan simetri: $\frac{x - 1}{2} = \frac{y + 2}{1} = \frac{z - 3}{-1}$

---

> **Contoh 3.24**
> Tentukan persamaan bidang yang melalui titik $(2, 1, 3)$ dan tegak lurus terhadap vektor $(3, -1, 2)$.
> 
> **Penyelesaian:**
> Vektor normal $\mathbf{n} = (3, -1, 2)$, titik $(2, 1, 3)$.
> $$3(x - 2) + (-1)(y - 1) + 2(z - 3) = 0 \implies 3x - y + 2z - 11 = 0$$

---

> **Contoh 3.25**
> Tentukan persamaan bidang yang melalui tiga titik $P(1, 0, 0)$, $Q(0, 2, 0)$, dan $R(0, 0, 3)$.
> 
> **Penyelesaian:**
> * $\vec{PQ} = (-1, 2, 0)$ dan $\vec{PR} = (-1, 0, 3)$
> * Vektor normal $\mathbf{n} = \vec{PQ} \times \vec{PR} = (6, 3, 2)$
> * Persamaan bidang: 
>     $$6(x - 1) + 3(y - 0) + 2(z - 0) = 0 \implies 6x + 3y + 2z = 6$$
> Dapat dibagi dengan 6 untuk mendapatkan bentuk *intercept*: $\frac{x}{1} + \frac{y}{2} + \frac{z}{3} = 1$.

---

> **Contoh 3.26**
> Tunjukkan dengan vektor bahwa diagonal-diagonal jajaran genjang saling membagi dua sama panjang.
> 
> **Penyelesaian:**
> Misalkan jajaran genjang $ABCD$ dengan $A$ sebagai titik asal.
> $\vec{AB} = \mathbf{b}$, $\vec{AD} = \mathbf{d}$. Maka $\vec{AC} = \mathbf{b} + \mathbf{d}$.
> * Titik tengah $AC$: $M_1 = \frac{\vec{AC}}{2} = \frac{\mathbf{b} + \mathbf{d}}{2}$
> * Titik tengah $BD$: $M_2 = \vec{AB} + \frac{\vec{BD}}{2} = \mathbf{b} + \frac{\mathbf{d} - \mathbf{b}}{2} = \frac{\mathbf{b} + \mathbf{d}}{2}$
> Karena $M_1 = M_2$, terbukti kedua diagonal berpotongan di titik yang sama dan saling membagi dua sama panjang. ✓

---

## 3.11 Aplikasi Vektor dalam Fisika

* **Gaya dan Hukum Newton:** Gaya adalah besaran vektor. Hukum II Newton dinyatakan sebagai:
    $$\mathbf{F} = m \cdot \mathbf{a}$$
* **Usaha (*Work*):** Diturunkan dari hasil kali skalar antara gaya $\mathbf{F}$ dan perpindahan $\mathbf{d}$:
    $$W = \mathbf{F} \cdot \mathbf{d}$$
* **Momen Gaya (*Torsi*):** Hasil kali silang vektor posisi $\mathbf{r}$ dengan vektor gaya $\mathbf{F}$:
    $$\boldsymbol{\tau} = \mathbf{r} \times \mathbf{F} \quad \implies |\boldsymbol{\tau}| = |\mathbf{r}| \cdot |\mathbf{F}| \cdot \sin \theta$$
* **Momentum Sudut:** Dituliskan sebagai:
    $$\mathbf{L} = \mathbf{r} \times \mathbf{p} \quad (\text{di mana } \mathbf{p} = m\mathbf{v})$$
* **Gaya Lorentz:** Gaya pada muatan $q$ bergerak berkecepatan $\mathbf{v}$ di medan magnet $\mathbf{B}$:
    $$\mathbf{F} = q(\mathbf{v} \times \mathbf{B})$$

---

> **Contoh 3.27**
> Sebuah gaya $\mathbf{F} = 3\mathbf{i} + 4\mathbf{j} - 2\mathbf{k}$ Newton menggerakkan suatu benda sepanjang lintasan dari titik $A(1, 2, 0)$ ke titik $B(4, 5, 6)$ meter. Hitung usaha yang dilakukan oleh gaya tersebut.
> 
> **Penyelesaian:**
> * Perpindahan: $\mathbf{d} = \vec{AB} = (3, 3, 6) \text{ meter}$
> * Usaha: $W = \mathbf{F} \cdot \mathbf{d} = (3)(3) + (4)(3) + (-2)(6) = 9 + 12 - 12 = 9 \text{ Joule}$

---

> **Contoh 3.28**
> Sebuah gaya $\mathbf{F} = (2, -1, 3)$ N bekerja pada benda di titik $(4, 2, 1)$ m. Hitung momen gaya (torsi) terhadap titik asal.
> 
> **Penyelesaian:**
> Vektor posisi $\mathbf{r} = (4, 2, 1) \text{ m}$.
> $$\boldsymbol{\tau} = \mathbf{r} \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 4 & 2 & 1 \\ 2 & -1 & 3 \end{vmatrix}$$
> $$= \mathbf{i}(6 - (-1)) - \mathbf{j}(12 - 2) + \mathbf{k}(-4 - 4) = 7\mathbf{i} - 10\mathbf{j} - 8\mathbf{k} \text{ N}\cdot\text{m}$$
> * Magnitudo: $|\boldsymbol{\tau}| = \sqrt{49 + 100 + 64} = \sqrt{213} \approx 14,59 \text{ N}\cdot\text{m}$


# BAB 4: GARIS DALAM RUANG DIMENSI TIGA (3D)

## 4.1 KONSEP DASAR VEKTOR ARAH DALAM RUANG 3D
Pada geometri analitik bidang atau ruang dimensi dua ($R^2$), kemiringan atau inklinasi suatu garis lurus dapat dinyatakan secara sederhana menggunakan satu nilai skalar yang disebut gradien ($m$). Nilai gradien ini diperoleh dari rasio perubahan nilai vertikal terhadap perubahan nilai horizontal ($\Delta y / \Delta x$). Namun, karakteristik geometris ini berubah secara drastis ketika kita beralih ke ruang dimensi tiga ($R^3$). Di dalam ruang 3D, sebuah garis memiliki kebebasan untuk condong atau miring ke berbagai arah ruang yang tak terbatas jumlahnya. Oleh karena itu, konsep kemiringan berbasis skalar tunggal kehilangan relevansi dan validitas matematisnya.

Untuk menentukan arah spesifik dari suatu garis lurus di dalam ruang dimensi tiga, kita memerlukan instrumen matematika berupa vektor. Arah suatu garis dalam ruang 3D ditentukan secara unik oleh sebuah vektor non-nol yang posisinya sejajar atau berimpit dengan garis tersebut. Vektor inilah yang disebut sebagai **Vektor Arah** ($\mathbf{v}$).

Secara formal, sebuah garis lurus $L$ di dalam ruang dimensi tiga dapat didefinisikan secara tunggal dan spesifik jika dan hanya jika diketahui dua elemen geometris berikut:
1. Sebuah titik tetap $P_0(x_0, y_0, z_0)$ yang terletak tepat pada lintasan garis $L$.
2. Sebuah vektor arah non-nol $\mathbf{v} = v_1\hat{i} + v_2\hat{j} + v_3\hat{k} = \langle v_1, v_2, v_3 \rangle$ yang sejajar dengan garis $L$.

>  **CONTOH SOAL: KONSEP VEKTOR ARAH**
> 
> **Soal:**
> Sebuah garis lurus $L$ di dalam ruang dimensi tiga diketahui memiliki sifat sejajar dengan vektor posisi yang dibentuk dari titik asal $O(0,0,0)$ menuju ke titik koordinat $M(4, -2, 6)$. Jika garis $L$ tersebut wajib melalui sebuah titik tetap $A(1, 3, 2)$, tentukan komponen vektor arah dari garis $L$ tersebut dan formulasikan representasi geometrisnya.
> 
> <div align="center">
>   <img src="https://i.ibb.co.com/TBpywFhY/4-1.png" width="500">
> </div>
> 
> **Penyelesaian:**
> * **Langkah 1:** Pahami sifat kesejajaran objek. Karena garis $L$ dinyatakan sejajar dengan vektor posisi $\overrightarrow{OM}$, maka berdasarkan hukum keselarasan arah, komponen vektor arah $\mathbf{v}$ dari garis $L$ secara langsung dapat diwakili oleh komponen vektor $\overrightarrow{OM}$ itu sendiri.
> * **Langkah 2:** Hitung komponen-komponen spasial dari vektor $\mathbf{v}$ melalui pengurangan koordinat titik ujung (*terminal point*) dengan titik pangkal (*initial point*):
> 
>   $$\mathbf{v} = \overrightarrow{OM} = \langle 4 - 0, -2 - 0, 6 - 0 \rangle = \langle 4, -2, 6 \rangle$$
> 
> * **Langkah 3:** Identifikasi parameter koordinat akhir. Titik acuan tetap yang dilalui garis adalah $P_0 = A(1, 3, 2)$ dengan komponen $x_0 = 1$, $y_0 = 3$, $z_0 = 2$. Vektor arah yang mengontrol kemiringan ruang dari garis ini adalah $\mathbf{v} = \langle 4, -2, 6 \rangle$, di mana nilai komponen arah skalarnya adalah $v_1 = 4$, $v_2 = -2$, dan $v_3 = 6$.

---

## 4.2 PERSAMAAN VEKTOR GARIS RECTILINEAR 3D
Setelah memahami peran vital dari vektor arah, kita dapat menurunkan persamaan matematika formal dari sebuah garis di ruang 3D. Pendekatan pertama dilakukan melalui analisis vektor posisi. Misalkan terdapat sebuah titik variabel bebas $P(x, y, z)$ yang terletak di sembarang posisi pada garis $L$. Garis $L$ ini sendiri memuat titik tetap $P_0(x_0, y_0, z_0)$ dan bergerak searah dengan vektor $\mathbf{v} = \langle v_1, v_2, v_3 \rangle$.

Jika kita menarik vektor dari titik asal $O(0,0,0)$ ke titik tetap $P_0$, kita mendapatkan vektor posisi $\mathbf{r}_0 = \langle x_0, y_0, z_0 \rangle$. Dengan cara yang sama, vektor posisi untuk titik variabel $P$ adalah $\mathbf{r} = \langle x, y, z \rangle$. Berdasarkan operasi penjumlahan vektor segitiga, vektor yang menghubungkan titik $P_0$ langsung ke titik variabel $P$ dapat dituliskan sebagai:

$$\overrightarrow{P_0P} = \mathbf{r} - \mathbf{r}_0$$

Secara geometris, karena titik $P_0$ dan $P$ keduanya berada pada garis $L$, maka vektor $\overrightarrow{P_0P}$ haruslah segaris (*collinear*) dan sejajar dengan vektor arah $\mathbf{v}$. Dua buah vektor dikatakan sejajar jika dan hanya jika salah satu vektor merupakan hasil perkalian skalar dari vektor lainnya. Oleh karena itu, terdapat suatu parameter bilangan real $t$ ( $-\infty < t < \infty$ ) sedemikian rupa sehingga memenuhi hubungan:

$$\overrightarrow{P_0P} = t\mathbf{v}$$

Substitusikan nilai $\overrightarrow{P_0P} = \mathbf{r} - \mathbf{r}_0$ ke dalam persamaan di atas:

$$\mathbf{r} - \mathbf{r}_0 = t\mathbf{v}$$

$$\mathbf{r} = \mathbf{r}_0 + t\mathbf{v}$$

Persamaan di atas merupakan **Persamaan Vektor dari Garis dalam Ruang 3D**. Setiap kali nilai parameter $t$ diubah dengan bilangan real apa pun, vektor posisi $\mathbf{r}$ akan menunjuk ke suatu titik spesifik di sepanjang garis $L$.

>  **CONTOH SOAL: PERSAMAAN VEKTOR**
> 
> **Soal:**
> Susunlah persamaan vektor untuk sebuah garis lurus $L$ dalam ruang dimensi tiga yang melintasi titik koordinat $P_0(-2, 0, 4)$ serta memiliki arah yang sejajar dengan vektor $\mathbf{v} = 2\hat{i} + 4\hat{j} - 2\hat{k}$.
> 
> <div align="center">
>   <img src="https://i.ibb.co.com/fbQxRfv/4-2.png" width="500">
> </div>
> 
> **Penyelesaian:**
> * **Langkah 1:** Transformasikan koordinat titik tetap $P_0$ menjadi bentuk komponen vektor posisi awal $\mathbf{r}_0$:
> 
>   $$\mathbf{r}_0 = \langle -2, 0, 4 \rangle$$
> 
> * **Langkah 2:** Tuliskan komponen dari vektor arah $\mathbf{v}$ yang diberikan ke dalam notasi kurung siku standar:
> 
>   $$\mathbf{v} = \langle 2, 4, -2 \rangle$$
> 
> * **Langkah 3:** Substitusikan komponen vektor $\mathbf{r}_0$ dan $\mathbf{v}$ ke dalam kerangka rumus umum persamaan vektor $\mathbf{r} = \mathbf{r}_0 + t\mathbf{v}$:
> 
>   $$\mathbf{r}(t) = \langle -2, 0, 4 \rangle + t\langle 2, 4, -2 \rangle$$
> 
>   $$\mathbf{r}(t) = \langle -2 + 2t, 4t, 4 - 2t \rangle$$

---

## 4.3 PERSAMAAN PARAMETRIK GARIS DALAM RUANG
Meskipun persamaan vektor memberikan landasan konsep yang kuat, dalam kalkulus analitis kita sering kali membutuhkan persamaan skalar terpisah untuk masing-masing sumbu koordinat. Kita dapat menurunkan persamaan ini dengan mengurai komponen-komponen pada persamaan vektor $\mathbf{r} = \mathbf{r}_0 + t\mathbf{v}$.

Mari kita tulis persamaan vektor tersebut dalam bentuk matriks komponen baris:

$$\langle x, y, z \rangle = \langle x_0, y_0, z_0 \rangle + t\langle v_1, v_2, v_3 \rangle$$

Lakukan operasi perkalian skalar $t$ dan penjumlahan vektor pada ruas kanan persamaan:

$$\langle x, y, z \rangle = \langle x_0 + tv_1, y_0 + tv_2, z_0 + tv_3 \rangle$$

Berdasarkan prinsip kesamaan dua buah vektor, dua vektor dikatakan sama jika dan hanya jika seluruh komponen yang bersesuaian pada kedua ruas bernilai sama. Dengan menyamakan komponen pada sumbu $X$, sumbu $Y$, dan sumbu $Z$, kita memperoleh sistem **Persamaan Parametrik Garis 3D**:

$$x = x_0 + tv_1$$

$$y = y_0 + tv_2$$

$$z = z_0 + tv_3$$

Di mana variabel $t$ bertindak sebagai parameter bebas real yang jangkauan nilainya membentang dari $-\infty$ hingga $+\infty$.

>  **CONTOH SOAL: PERSAMAAN PARAMETRIK**
> 
> **Soal:**
> Carilah sistem persamaan parametrik dari sebuah garis lurus di ruang 3D yang melintasi dua titik eksternal yaitu titik $A(5, 1, 3)$ dan titik $B(2, 6, -1)$.
> 
> <div align="center">
>   <img src="https://i.ibb.co.com/nq00hQqg/4-3.png" width="500">
> </div>
> 
> **Penyelesaian:**
> * **Langkah 1 (Uji Kesejajaran):** Ekstrak vektor arah masing-masing komponen: $\mathbf{v}_1 = \langle 1, 3, -1 \rangle$ dan $\mathbf{v}_2 = \langle 2, 1, 4 \rangle$. Periksa perbandingan rasionya:
> 
>   $$\frac{1}{2} \neq \frac{3}{1} \neq \frac{-1}{4}$$
> 
>   Karena rasio antar komponennya tidak bernilai konstan, maka kedua garis tidak sejajar.
> 
> * **Langkah 2 (Uji Titik Potong pada Sumbu X dan Y):**
>   * Samakan komponen $x$ 
>     $$1 + t = 2s \implies t = 2s - 1 \quad \text{(Persamaan i)}$$
>   * Samakan komponen $y$ 
>     $$-2 + 3t = 3 + s \quad \text{(Persamaan ii)}$$
>   * Substitusikan Persamaan (i) ke dalam Persamaan (ii):
> 
>     $$-2 + 3(2s - 1) = 3 + s \implies 5s = 8 \implies s = 1.6$$
> 
>   * Setelah itu, hitung nilai parameter $t$:
>     $$t = 2(1.6) - 1 = 2.2$$
> 
> * **Langkah 3 (Uji Konsistensi Nilai pada Sumbu Z):**
>   Uji pasangan nilai parameter $t = 2.2$ dan $s = 1.6$ pada komponen $z$:
>   * Untuk Garis $L_1 \implies z = 4 - t = 4 - 2.2 = 1.8$
>   * Untuk Garis $L_2 \implies z = -3 + 4s = -3 + 4(1.6) = 3.4$
> 
>   Karena hasil perhitungan koordinat $z$ menghasilkan nilai yang berbeda ($1.8 \neq 3.4$), maka sistem persamaan tersebut mengalami kontradiksi.
---

## 4.4 PERSAMAAN SIMETRIS GARIS DALAM RUANG
Terdapat metode alternatif untuk menyatakan sebuah garis di dalam ruang tanpa melibatkan parameter $t$, yaitu dengan menggunakan hubungan rasio spasial. Pendekatan ini dapat dilakukan apabila seluruh komponen skalar pada vektor arah memiliki nilai non-nol ($v_1 \neq 0, v_2 \neq 0, v_3 \neq 0$).

Perhatikan kembali sistem persamaan parametrik dasar yang kita miliki:
1. Dari persamaan $x = x_0 + tv_1$, jika kita isolasi variabel $t$, didapatkan: $t = \frac{x - x_0}{v_1}$
2. Dari persamaan $y = y_0 + tv_2$, jika kita isolasi variabel $t$, didapatkan: $t = \frac{y - y_0}{v_2}$
3. Dari persamaan $z = z_0 + tv_3$, jika kita isolasi variabel $t$, didapatkan: $t = \frac{z - z_0}{v_3}$

Karena parameter $t$ pada ketiga persamaan di atas merujuk pada satu nilai koordinat waktu yang sama di sepanjang garis, maka kita dapat mengeliminasi variabel $t$ dan menyamakan ketiga nilai rasio tersebut secara kontinu:

$$\frac{x - x_0}{v_1} = \frac{y - y_0}{v_2} = \frac{z - z_0}{v_3}$$

Hubungan kesamaan rasio tripel di atas dinamakan sebagai **Persamaan Simetris Garis 3D**.

*Catatan Pengecualian:* Jika salah satu komponen vektor arah bernilai nol, misalnya $v_3 = 0$, maka kita tidak boleh melakukan pembagian dengan nol. Persamaan simetrisnya dimodifikasi dengan cara memisahkan komponen yang bernilai nol tersebut:

$$\frac{x - x_0}{v_1} = \frac{y - y_0}{v_2}, \quad z = z_0$$

>  **CONTOH SOAL: PERSAMAAN SIMETRIS** > 
> **Soal:**
> Diketahui sebuah garis lurus dalam ruang memiliki struktur persamaan parametrik $x = 1 + 2t$, $y = 3 - 4t$, dan $z = 5 + 6t$. Ubahlah bentuk persamaan tersebut menjadi bentuk persamaan simetris.
> 
> <div align="center">
>   <img src="https://i.ibb.co.com/4wf8Wvj7/4-4.png" width="500">
> </div>
> 
> **Penyelesaian:**
> * **Langkah 1:** Identifikasi koordinat titik tetap ($x_0, y_0, z_0$) dan nilai komponen vektor arah ($v_1, v_2, v_3$) dari persamaan parametrik:
>   * Dari $x = 1 + 2t \implies x_0 = 1, \ v_1 = 2$
>   * Dari $y = 3 - 4t \implies y_0 = 3, \ v_2 = -4$
>   * Dari $z = 5 + 6t \implies z_0 = 5, \ v_3 = 6$
> * **Langkah 2:** Masukkan seluruh nilai komponen skalar tersebut ke dalam rumus dasar persamaan simetris:
> 
>   $$\frac{x - 1}{2} = \frac{y - 3}{-4} = \frac{z - 5}{6}$$
> 
> * **Langkah 3:** Sederhanakan bagian penyebut dengan mengalikan seluruh bagian dengan angka 2:
> 
>   $$\frac{x - 1}{1} = \frac{y - 3}{-2} = \frac{z - 5}{3}$$

---

## 4.5 PERSAMAAN SEGMEN GARIS TERBATAS
Dalam berbagai aplikasi rekayasa, fisika, dan grafika komputer, kita sering kali tidak berhadapan dengan sebuah garis lurus utuh yang panjangnya tak terbatas. Sering kali kita hanya perlu menganalisis sepotong bagian garis yang dibatasi oleh dua buah titik, yaitu dimulai dari titik awal $P_0(x_0, y_0, z_0)$ dan berakhir di titik tujuan $P_1(x_1, y_1, z_1)$. Objek geometri terikat ini disebut sebagai **Segmen Garis** (*Line Segment*).

Untuk membentuk persamaannya, kita tentukan dahulu vektor arah yang menghubungkan $P_0$ langsung ke $P_1$:

$$\mathbf{v} = \overrightarrow{P_0P_1} = \mathbf{r}_1 - \mathbf{r}_0 = \langle x_1 - x_0, y_1 - y_0, z_1 - z_0 \rangle$$

Substitusikan vektor arah spesifik ini ke dalam landasan persamaan vektor dasar $\mathbf{r} = \mathbf{r}_0 + t\mathbf{v}$:

$$\mathbf{r}(t) = \mathbf{r}_0 + t(\mathbf{r}_1 - \mathbf{r}_0)$$

Lakukan perluasan aljabar dan kelompokkan suku-suku berdasarkan vektor posisinya:

$$\mathbf{r}(t) = \mathbf{r}_0 + t\mathbf{r}_1 - t\mathbf{r}_0$$

$$\mathbf{r}(t) = (1 - t)\mathbf{r}_0 + t\mathbf{r}_1$$

Agar persamaan di atas menghasilkan sepotong segmen garis yang presisi dan tidak meluas tanpa batas, kita wajib menerapkan batasan nilai parameter $t$ pada interval tertutup:

$$0 \leq t \leq 1$$

* Jika kita memasukkan nilai $t = 0$, maka persamaan menghasilkan $\mathbf{r}(0) = \mathbf{r}_0$ (posisi tepat berada di titik awal $P_0$).
* Jika kita memasukkan nilai $t = 1$, maka persamaan menghasilkan $\mathbf{r}(1) = \mathbf{r}_1$ (posisi tepat berada di titik akhir $P_1$).

>  **CONTOH SOAL: SEGMEN GARIS**
> 
> **Soal:**
> Formulasikan persamaan parametrik yang memodelkan segmen ruas garis dengan ujung-ujung yang mengikat dari titik awal $P_0(2, 4, -1)$ hingga mencapai titik akhir $P_1(5, 0, 7)$ di dalam ruang 3D.
> 
> <div align="center">
>   <img src="https://i.ibb.co.com/YBg0V8gg/4-5.png" width="500">
> </div>
> 
> **Penyelesaian:**
> * **Langkah 1:** Catat elemen koordinat pada masing-masing titik ujung segmen:
> 
>   $$x_0 = 2, \ y_0 = 4, \ z_0 = -1 \quad \text{dan} \quad x_1 = 5, \ y_1 = 0, \ z_1 = 7$$
> 
> * **Langkah 2:** Gunakan perumusan komponen segmen garis $x = x_0 + t(x_1 - x_0)$ untuk masing-masing sumbu koordinat:
>   * $x = 2 + t(5 - 2) = 2 + 3t$
>   * $y = 4 + t(0 - 4) = 4 - 4t$
>   * $z = -1 + t(7 - (-1)) = -1 + 8t$
> * **Langkah 3:** Gabungkan ketiga komponen skalar tersebut beserta dengan syarat batas interval:
> 
>   $$x = 2 + 3t, \quad y = 4 - 4t, \quad z = -1 + 8t \quad \text{di mana } 0 \leq t \leq 1$$

---

## 4.6 KLASIFIKASI HUBUNGAN GEOMETRIS ANTARA DUA BUAH GARIS
Di dalam ruang dimensi dua ($R^2$), dua buah garis yang berbeda hanya memiliki dua kemungkinan hubungan posisi: jika tidak sejajar, kedua garis tersebut pasti akan berpotongan di suatu titik. Namun, di dalam ruang dimensi tiga ($R^3$), terdapat tiga kemungkinan hubungan posisi antara dua buah garis yang berbeda ($L_1$ dengan vektor arah $\mathbf{v}_1$ dan $L_2$ dengan vektor arah $\mathbf{v}_2$):

### 4.6.1 Garis-Garis Sejajar (*Parallel Lines*)
Dua buah garis dikatakan sejajar jika dan hanya jika vektor arah dari kedua garis tersebut memiliki orientasi yang sama atau berlawanan arah, yang ditandai dengan sifat kelipatan skalar:

$$\mathbf{v}_1 = k\mathbf{v}_2, \quad \text{di mana } k \in R \text{ dan } k \neq 0$$

### 4.6.2 Garis-Garis Berpotongan (*Intersecting Lines*)
Dua buah garis dikatakan berpotongan jika keduanya tidak sejajar, namun memiliki satu titik persekutuan tunggal $P(x,y,z)$ yang sama. Untuk membuktikan hubungan ini, kita harus menyelesaikan sistem persamaan parametrik dari kedua garis secara simultan menggunakan dua variabel parameter yang berbeda (misalnya parameter $t$ untuk garis $L_1$ dan parameter $s$ untuk garis $L_2$).

### 4.6.3 Garis-Garis Bersilangan (*Skew Lines*)
Garis bersilangan merupakan fenomena geometris yang unik dan hanya terjadi pada ruang dimensi tiga atau lebih tinggi. Dua buah garis dikatakan bersilangan jika keduanya **tidak saling sejajar** dan **tidak pernah berpotongan** meskipun ditarik sepanjang apa pun. Hal ini terjadi karena kedua garis berada pada dua lapisan bidang sejajar yang berbeda di dalam ruang.

>  **CONTOH SOAL: HUBUNGAN DUA GARIS**
> 
> **Soal:**
> Lakukan analisis analitis menyeluruh untuk menentukan hubungan geometris antara dua garis berikut, apakah berpotongan atau bersilangan:
> 
> $$L_1: x = 1 + t, \quad y = -2 + 3t, \quad z = 4 - t$$
> 
> $$L_2: x = 2s, \quad y = 3 + s, \quad z = -3 + 4s$$
> 
> <div align="center">
>   <img src="https://i.ibb.co.com/cXNHXcFC/4-6.png" width="500">
> </div>
> 
> **Penyelesaian:**
> * **Langkah 1 (Uji Kesejajaran):** Ekstrak vektor arah masing-masing komponen: $\mathbf{v}_1 = \langle 1, 3, -1 \rangle$ dan $\mathbf{v}_2 = \langle 2, 1, 4 \rangle$. Periksa perbandingan rasionya:
> 
>   $$\frac{1}{2} \neq \frac{3}{1} \neq \frac{-1}{4}$$
> 
>   Karena rasio antar komponennya tidak bernilai konstan, maka **kedua garis tidak sejajar**.
> * **Langkah 2 (Uji Titik Potong pada Sumbu X dan Y):**
>   * Samakan komponen $x$: $1 + t = 2s \implies t = 2s - 1 \quad (\text{Persamaan i})$
>   * Samakan komponen $y$: $-2 + 3t = 3 + s \quad (\text{Persamaan ii})$
>   * Substitusikan Persamaan (i) ke dalam Persamaan (ii):
>     $$-2 + 3(2s - 1) = 3 + s \implies 5s = 8 \implies s = 1.6$$
>   * Setelah itu, hitung nilai parameter $t$: $t = 2(1.6) - 1 = 2.2$
> * **Langkah 3 (Uji Konsistensi Nilai pada Sumbu Z):**
>   Uji pasangan nilai parameter $t = 2.2$ dan $s = 1.6$ pada komponen $z$:
>   * Untuk Garis $L_1 \implies z = 4 - t = 4 - 2.2 = 1.8$
>   * Untuk Garis $L_2 \implies z = -3 + 4s = -3 + 4(1.6) = 3.4$
>   Karena hasil perhitungan koordinat $z$ menghasilkan nilai yang berbeda ( $1.8 \neq 3.4$ ), maka sistem persamaan tersebut mengalami kontradiksi (inkonsisten).
> * **Kesimpulan:** Karena kedua garis tidak memiliki arah yang sejajar dan tidak memiliki titik potong persekutuan, maka hubungan antara garis $L_1$ dan $L_2$ adalah **Bersilangan** (*Skew Lines*).

---

## 4.7 PERHITUNGAN JARAK TEGAK LURUS DARI SEBUAH TITIK KE GARIS
Misalkan terdapat sebuah titik $S$ yang berada di luar sebuah garis lurus $L$ di dalam ruang 3D. Garis $L$ tersebut diketahui memuat titik tetap $P_0$ dan bergerak searah dengan vektor arah $\mathbf{v}$. Jarak terpendek atau jarak tegak lurus $d$ dari titik $S$ menuju garis $L$ dapat ditentukan dengan memanfaatkan operasi perkalian silang (*cross product*).

Perhatikan segitiga siku-siku yang dibentuk oleh titik tetap $P_0$, titik luar $S$, dan proyeksi tegak lurus titik $S$ pada garis $L$. Panjang sisi miring dari segitiga ini diwakili oleh magnitudo dari vektor $\overrightarrow{P_0S}$. Jika $\theta$ menyatakan sudut lancip yang terbentuk antara vektor $\overrightarrow{P_0S}$ dengan vektor arah garis $\mathbf{v}$, maka berdasarkan perbandingan trigonometri, jarak tegak lurus $d$ dapat dituliskan sebagai:

$$d = |\overrightarrow{P_0S}| \sin \theta$$

Berdasarkan definisi geometris dari operasi perkalian silang antara dua buah vektor, magnitudo dari hasil kali silang vektor $\overrightarrow{P_0S}$ dengan vektor arah $\mathbf{v}$ memenuhi hubungan persamaan berikut:

$$|\overrightarrow{P_0S} \times \mathbf{v}| = |\overrightarrow{P_0S}| |\mathbf{v}| \sin \theta$$

Substitusikan hubungan trigonometri $|\overrightarrow{P_0S}| \sin \theta = d$ ke dalam persamaan perkalian silang di atas:

|$$\overrightarrow{P_0S} \times \mathbf{v}| = d \cdot |\mathbf{v}|$$

Dengan mengisolasi variabel $d$, kita mendapatkan rumus baku untuk menghitung **Jarak Titik ke Garis dalam Ruang 3D**:

$$d = \frac{|\overrightarrow{P_0S} \times \mathbf{v}|}{|\mathbf{v}|}$$

>  **CONTOH SOAL: JARAK TITIK KE GARIS**
> 
> **Soal:**
> Hitunglah jarak tegak lurus $d$ yang membentang dari sebuah titik luar $S(1, 1, 5)$ menuju ke sebuah garis lurus $L$ yang memiliki rumusan persamaan parametrik $x = 1 + 2t$, $y = -1 + 3t$, dan $z = 4 + t$.
> 
> <div align="center">
>   <img src="https://i.ibb.co.com/fYnZ4QxT/4-7.png" width="500">
> </div>
> 
> **Penyelesaian:**
> * **Langkah 1:** Ekstrak data dari persamaan parametrik garis $L$: Titik tetap $P_0(1, -1, 4)$ dan vektor arah $\mathbf{v} = \langle 2, 3, 1 \rangle$.
> * **Langkah 2:** Hitung komponen vektor posisi $\overrightarrow{P_0S}$ yang menghubungkan titik tetap $P_0$ ke titik luar $S$:
> 
>   $$\overrightarrow{P_0S} = \langle 1 - 1, 1 - (-1), 5 - 4 \rangle = \langle 0, 2, 1 \rangle$$
> 
> * **Langkah 3:** Hitung operasi perkalian silang (*cross product*) $\overrightarrow{P_0S} \times \mathbf{v}$ menggunakan determinan matriks $3 \times 3$:
> 
>   $$\overrightarrow{P_0S} \times \mathbf{v} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 0 & 2 & 1 \\ 2 & 3 & 1 \end{vmatrix} = \hat{i}(2 - 3) - \hat{j}(0 - 2) + \hat{k}(0 - 4) = \langle -1, 2, -4 \rangle$$
> 
> * **Langkah 4:** Hitung nilai magnitudo (panjang) dari vektor hasil perkalian silang dan vektor arah $\mathbf{v}$:
> 
>   $$|\overrightarrow{P_0S} \times \mathbf{v}| = \sqrt{(-1)^2 + (2)^2 + (-4)^2} = \sqrt{21}$$
> 
>   $$|\mathbf{v}| = \sqrt{(2)^2 + (3)^2 + (1)^2} = \sqrt{14}$$
> 
> * **Langkah 5:** Masukkan kedua nilai magnitudo tersebut ke dalam rumus jarak $d$:
> 
>   $$d = \frac{\sqrt{21}}{\sqrt{14}} = \sqrt{\frac{3}{2}} = \frac{1}{2}\sqrt{6} \approx 1.22$$

---

## DAFTAR PUSTAKA ACUAN DAN HALAMAN SUMBER

* **Riddle, Douglas F.** (1996). *Analytic Geometry, Sixth Edition*. Boston: PWS Publishing Company.
    * *Rujukan Sub-bab 4.1 & 4.2 (Transformasi Koordinat, Teori Vektor Arah, dan Penurunan Komponen Vektor Ruang)* $\rightarrow$ Diadopsi dan disintesis secara analitis dari Bab 6 (*Transformation of Coordinates and Vectors in Space*), **Halaman 195–201**.
* **Stewart, James.** (2012). *Calculus: Early Transcendentals, Seventh Edition (Multivariable Volume)*. Belmont: Brooks/Cole Cengage Learning.
    * *Rujukan Sub-bab 4.3, 4.4, & 4.6 (Sistem Persamaan Parametrik, Rasio Kesamaan Simetris, dan Teorema Klasifikasi Garis Bersilangan)* $\rightarrow$ Diadopsi secara akurat dari Chapter 12 (*Vectors and the Geometry of Space*), Section 12.5 (*Lines and Planes in Space*), **Halaman 559–561**.
* **Thomas Jr., George B., Weir, Maurice D., & Hass, Joel.** (2014). *Thomas' Calculus: Early Transcendentals, Thirteenth Edition*. Boston: Pearson Education, Inc.
    * *Rujukan Sub-bab 4.5 & 4.7 (Formulasi Batasan Parameter Ruas Garis Tertentu dan Penurunan Jarak Berbasis Operasi Cross-Product Vektor)* $\rightarrow$ Diadopsi secara ketat dari Chapter 12 (*Vectors and the Geometry of Space*), Section 12.5, **Halaman 732–735**.
