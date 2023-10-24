---
title: "Eksponensial: Bagian Pertama"
author: Darrel
date: 2023-10-24 09:24:30 +0700
categories: [SMP, Matematika]
tags: [Sifat Eksponen]
math: True
---

## Prasyarat
Sebelum kamu masuk pada materi eksponen ini, kami sangat berharap kamu mengerti dan hafal tabel perkalian. Selain itu, kami harap kamu juga mengerti perkalian dengan pecahan maupun bilangan bulat

## Motivasi
Kita ingin belajar sifat eksponen untuk menyederhanakan perhitungan matematika. Oleh karena itu, kita membutuhkan sebuah _tool_ (alat) yang dapat kita gunakan untuk mempermudah kita untuk menyederhanakan perhitungan matematika. Misalkan saja saya ingin melakukan perhitungan:

$$\frac{2^{50}}{20^5}\cdot \frac{3^{10}}{2^{25}}$$

Jika kita tidak menggunakan kalkulator, perhitungan ini akan sangat sulit. Bahkan jika kita memiliki kalkulator, kalkulator kita bisa saja tidak bisa menangani angka yang besar tersebut (baca konsep _overflow_). 

## Definisi Eksponen
Eksponen didefinisikan sebagai berikut:

$$a^n=\underbrace{a\cdot a\cdot a \cdots a}_{n}$$

Perhatikan bahwa definisi diatas pada dasarnya sedang mengatakan $a^n$ berarti bilangan a dikalikan dengan dirinya sebanyak n kali.

## Contoh Eksponen
Supaya kamu bisa lebih mengerti tentang konsep eksponen, mari melihat beberapa contoh soal eksponen.

### Contoh 1

Kita ingin mencari tau nilai $2^3$. Untuk mencari tahu nilai tersebut, artinya kita tinggal mengalikan $2$ dengan dirinya sendiri sebanyak $3$ kali. 

$$2^3=2\cdot 2\cdot 2=2 \cdot 4=8$$

Jadi, hasil dari $2^3$ adalah $8$. **Ingat bahwa $2^3 \neq 2\cdot 3$.** Perhatikan bahwa $8\neq 6$. Ini merupakan kesalahan yang sering terjadi ketika kita baru berkenalan dengan sifat eksponen ini.

### Contoh 2
Berapakah hasil $4^5$? Sama seperti contoh 1, kita bisa mencarinya dengan mengalikan $4$ dengan dirinya sendiri sebanyak $5$ kali. 

$$
\begin{align*}
4^3 & = 4 \cdot 4 \cdot 4 \cdot 4 \cdot 4\\
    & = 16 \cdot 16 \\
    & = 256
\end{align*}
$$

### Contoh 3
Setelah melihat beberapa contoh bilangan bulat positif yang dipangkatkan, mari kita coba lihat bagaimana jika bilangan negatif dipangkatkan. Misalkan soalnya $(-5)^3$. Bagaimana kita mencarinya?

$$
\begin{align*}
(-5)^3 & = (-5) \cdot (-5) \cdot (-5)\\
    & = 25 \cdot (-5) \\
    & = -125
\end{align*}
$$

Jadi, hasilnya adalah $-125$

### Contoh 4
Mari kita lihat contoh bilangan negatif lain yang dipangkatkan. Dalam contoh ini kita akan mengerjakan $(-3)^4$.

$$
\begin{align*}
(-3)^4 & = (-3) \cdot (-3) \cdot (-3) \cdot (-3)\\
    & = 9 \cdot 9 \\
    & = 81
\end{align*}
$$

Jadi hasilnya adalah 81.

### Contoh 5
Agar lebih mantap, mari kita coba lagi eksponen tetapi dengan bilangan pecahan. Ingat bahwa konsepnya sama saja, kamu perlu mengalikan bilangan $a$ sebanyak $n$ kali. Sekarang, mari kita mencoba mencari tahu nilai $\left(\frac{1}{2}\right)^8$. Cobalah kerjakan sendiri terlebih dahulu sebelum melihat jawabannya.

$$
\begin{align*}
\left(\frac{1}{2}\right)^8 & = \frac{1}{2} \cdot \frac{1}{2} \cdot \frac{1}{2} \cdot \frac{1}{2} \cdot \frac{1}{2} \cdot \frac{1}{2} \cdot \frac{1}{2} \cdot \frac{1}{2} \\
    & = \frac{1}{4} \cdot \frac{1}{4} \cdot \frac{1}{4} \cdot \frac{1}{4} \\
    & = \frac{1}{16} \cdot \frac{1}{16} \\
    & = \frac{1}{256}
\end{align*}
$$

Jadi, hasilnya adalah $\frac{1}{16}$

## Sifat Eksponen (bagian pertama)
Perhatikan contoh 3 dan contoh 4. Ketika kamu melakukan pangkat pada `bilangan negatif` dengan pangkat yang bernilai `genap`, maka hasilnya akan selalu `positif`. Sedangkan, jika kamu melakukan pangkat pada `bilangan negatif` dengan pangkat yang bernilai `ganjil`, maka hasilnya akan selalu `negatif`. Secara matematis, berlaku:

$$
\begin{align*}
(-a)^n &= a^n && \text{Dimana } n \text{ adalah bilangan genap} \\
(-a)^n &= -(a^n) && \text{Dimana } n \text{ adalah bilangan ganjil}
\end{align*}
$$

Jika kamu adalah penggemar matematika, kita akan membuktikan sifat eksponen tersebut pada bagian dibawah ini. Tetapi, jika kamu bukan merupakan penggemar matematika, kamu bisa langsung menerima rumus tersebut dan melanjutkan ke bagian selanjutnya, yaitu tentang sifat-sifat eksponen yang lain.

### Pembuktian
Cobalah amati dan kerjakan beberapa soal tersebut dan lihat apa yang bisa kamu temukan.
1. $(-2)^1$
2. $(-2)^2$
3. $(-2)^3$
4. $(-2)^4$
5. $(-2)^5$
6. $(-3)^1$
7. $(-3)^2$
8. $(-3)^3$
9. $(-3)^4$
10. $(-3)^5$

Jika kamu perhatikan, kamu bisa melihat untuk $a=-2$ dan $a=-3$, setiap kita menaikkan n sebanyak 1, tandanya akan berganti. Tetapi mengapa hal ini terjadi? Mari kita tinjau dari $2^3$ dan $2^4$.

$$
\begin{align*}
(-2)^3 & = (-2) \cdot (-2) \cdot (-2)\\
    & = 4 \cdot -2 \\
    & = -8
\end{align*}
$$

$$
\begin{align*}
(-2)^4 & = (-2) \cdot (-2) \cdot (-2) \cdot (-2)\\
    & = 4 \cdot 4 \\
    & = 16
\end{align*}
$$

Perhatikan bahwa ada pada tahap kedua, ketika kita sedang mengalikan (-2) dengan dirinya sendiri, pada $(-2)^3$ bilangan yang dikalikan dengan $4$ adalah $-2$. Tanda negatif pada 2 inilah yang membuat perkalian tersebut negatif. 

Pada lain sisi, pada $(-2)^4$, pada tahapan kedua semua bilangannya positif, yaitu $4$ dan $4$. Hal ini akan mengakibatkan hasilnya positif juga.

Secara umum, sifat ini dapat dibuktikan seperti ini: jika sebuah bilangan negatif dipangkatkan dengan bilangan `genap`, perkalian bilangan-bilangan negatif tersebut `memiliki pasangannya`. Kemudian karena pasangannya genap, maka pastilah hasil bilangannya adalah bilangan genap.

Sedangkan, jika sebuah bilangan negatif dipangkatkan dengan `bilangan ganjil`, perkalian bilangan-bilangan negatif memiliki pasangan `kecuali` 1 bilangan lain. 1 bilangan lain inilah yang tidak memiliki pasangan yang akan menyebabkan hasilnya menjadi negatif.

#### Penutup
Selamat, kamu sudah membuktikan sifat eksponen pada bagian pertama ini. Kami harap usahamu untuk mengerti materi yang diberikan pada blog ini tidak sia-sia. Selanjutnya, mari kita belajar mengenai sifat-sifat ekponen yang lain pada blog ekponensial bagian kedua.