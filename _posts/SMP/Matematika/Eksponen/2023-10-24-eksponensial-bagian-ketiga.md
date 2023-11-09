---
title: "Eksponensial: Bagian Ketiga"
author: Darrel
date: 2023-10-24 16:44:30 +0700
categories: [SMP, Matematika]
tags: [Sifat Eksponen]
math: True
---

## Prasyarat
Kami harap kamu sudah membaca blog saya pada bagian kedua, karena pada bagian ini saya akan menjelaskan tentang solusi dari pertanyaan yang disajikan (sebagai _snack_) bagi kalian pada [blog sebelumnya](). Selain itu, kami juga ingin menjelaskan bagaimana cara menjawab soal pada bagian pertama. Terakhir, kami akan memberikan contoh bagaimana cara menyederhanakan bentuk aljabar dengan sifat-sifat maupun definisi eksponen yang ada.

## Jawaban untuk 15 Pertanyaan Sebelumnya
1. $10^2\cdot 10^2$
   - Kita bisa menggunakan aturan eksponen: $a^m \cdot a^n = a^{m+n}$
     - $10^2\cdot 10^2 = 10^{2+2}$
     - $10^{2+2} = 10^4 = 10000$
   - Perhatikan bahwa $10^n$ berarti kita hanya perlu menambahkan $n$ buah angka 0 setelah angka 1. Perhatikan bahwa trik ini akan sangat berguna untuk soal nomor 12.

2. $5^2\cdot 5^3$
   - Menggunakan aturan eksponen yang sama seperti pada soal 1.
     - $5^2\cdot 5^3 = 5^{2+3}$
     - $5^{2+3} = 5^5=3125$

3. $25^2 \cdot 5^2$
   - Gunakan aturan eksponen: $(a^m)^n = a^{m\cdot n}$
     - $(25^2) \cdot (5^2) = 25^{2\cdot 2}$
     - $25^{2\cdot 2} = 25^4 = 390625$

4. $6^3 \cdot 3^2$
   - Menggunakan aturan eksponen untuk perkalian seperti pada soal 1.
     - $6^3 \cdot 3^2 = 6^{3+2}$
     - $6^{3+2} = 6^5 = 7776$

5. $\left(\frac{2}{3}\right)^5$
   - Untuk memangkatkan pecahan ke suatu eksponen, kita memangkatkan pembilang dan penyebutnya.
     - $\left(\frac{2}{3}\right)^5 = \frac{2^5}{3^5}$

6. $\left(-\frac{4}{3}\right)^5$
   - Sama seperti soal 5, namun dengan pecahan negatif.
     - $\left(-\frac{4}{3}\right)^5 = \left(-\frac{4^5}{3^5}\right)$

7. $\left(-\frac{3}{3}\right)^5$
   - Karena pembilang dan penyebut sama, pecahan ini dapat disederhanakan.
     - $\left(-\frac{3}{3}\right)^5 = (-1)^5 = -1$

8. $(2^4)^3$
   - Menggunakan aturan eksponen untuk pemangkatan seperti pada soal 3.
     - $(2^4)^3 = 2^{4\cdot3}$
     - $2^{4\cdot3} = 2^{12} = 4096$

9. $(2^3)^4$
   - Sama seperti soal 8, menggunakan aturan eksponen untuk pemangkatan.
     - $(2^3)^4 = 2^{3\cdot4}$
     - $2^{3\cdot4} = 2^{12} = 4096$

10. $(1^2)^3$
   - Apapun yang dipangkatkan ke eksponen 1 adalah bilangan itu sendiri.
     - $(1^2)^3 = 1^3 = 1$

11. $(4\cdot 5)^{2}$
   - Terlebih dahulu, kita evaluasi ekspresi dalam tanda kurung.
     - $(4\cdot 5)^{2} = 20^2=400$


12. $(4\cdot 5)^{10}$
   - Terlebih dahulu, kita evaluasi ekspresi dalam tanda kurung.
     - $(4\cdot 5)^{10} = 20^{10}$
   - Lebih mudah jika kita memisah 20 menjadi $2\cdot 10$
     - $(2\cdot 10)^{10}=2^{10}\cdot 10^10=10240000000000$

13. $2^{\frac{5}{3}}$
   - Untuk memangkatkan bilangan dengan eksponen pecahan, kita menggunakan akar ke-n.
     - $2^{\frac{5}{3}} = \sqrt[3]{2^5}=\sqrt[3]{32}$
     - Tetapi, $\sqrt[3]{2^5}$ bisa juga dituliskan sebagai $2\sqrt[3]{4}$ karena $\sqrt[3]{2^5}=\sqrt[3]{2^3\cdot 2^2}=2\sqrt[3]{2^2}=2\sqrt[3]{4}$

14. $3^{-5}$
   - Eksponen negatif menunjukkan bilangan tersebut menjadi pecahan.
     - $3^{-5} = \frac{1}{3^5} = \frac{1}{243}$
     - Atau jika kita ingin menghitung nilai pastinya

15. Apakah bisa $0^{-6}$?
   - Jawabnya adalah tidak.
     - Tidak, karena 0 tidak boleh dipangkatkan dengan bilangan negatif


Saya harap kamu dapat menyelesaikan soal-soal tersebut. Tidak apa-apa jika kamu melakukan kesalahan, karena dengan kesalahan, kamu bisa belajar untuk tidak mengulangi hal yang salah bukan? Selanjutnya, kita akan membahas bagaimana cara menyederhanakan persamaan aljabar dengan eksponen.


## Penyederhanaan Ekspresi Aljabar
Salah satu tujuan utama kita mempelajari materi eksponen ini adalah untuk menyederhanakan ekspresi aljabar. Oleh karena itu, pada bagian ini kita akan mempelajari bagaimana caranya. Sebenarnya caranya sama saja dengan bagian atas. Hal yang membedakan adalah kita akan menggunakan huruf dan menyederhanakan ekspresi yang ada supaya lebih sederhana. Idenya kurang lebih sama saja seperti kita ingin menyederhanakan pecahan yang belum sederhana.

## Contoh 1
Sederhanakanlah ekspresi berikut:

$$\left(\frac{3^{2x+1} \cdot 2^{x-2}}{6^{x-1}}\right)$$

Tahapan untuk mengerjakan soal diatas adalah sebagai berikut:

1. Bersyukur. Tahapan ini merupakan tahapan yang saya dapati ketika belajar dari salah satu dosen saya. Kita perlu bersyukur karena kita diberikan soal ini dan kita dapat melatih kemampuan kita. 
2. Perhatikan bagian mana saja yang dapat kita pecah menggunakan sifat-sifat dan definisi-definisi yang kita miliki. Dalam kasus ini, kita bisa melihat bahwa pangkat yang ditambah bisa dipecah. Kita juga bisa lihat bahwa $6=2\cdot 3$
3. Kerjakan.
<details close>
<summary> Click to see answer</summary>
$$
\begin{align*}
\frac{3^{2x+1} \cdot 2^{x-2}}{6^{x-1}} & = \frac{3^{2x+1} \cdot 2^{x-2}}{(2\cdot 3)^{x-1}}\\
&= \frac{3^{2x+1} \cdot 2^{x-2}}{3^{x-1} \cdot 2^{x-1}}\\
&= \frac{3^{2x+1}}{3^{x-1}} \cdot \frac{2^{x-2}}{2^{x-1}}\\
&= 3^{((2x+1)-(x-1))} \cdot 2^{((x-2)-(x-1))}\\
&= 3^{(2x+1-x+1)} \cdot 2^{(x-2-x+1)} \\
&= 3^{3x} \cdot 2^{-1}\\
&= \frac{3^{3x}}{2}
\end{align*}
$$
</details>

## Contoh 2
Selanjutnya, mari kita coba mengerjakan soal yang melibatkan akar. Sederhanakanlah ekspresi berikut:

$$\sqrt[3]{a^6} \cdot \sqrt[4]{a^9}$$

Untuk mengerjakan soal berikut, kita bisa mengikuti tahapan-tahapan yang ada pada soal contoh 1. Mengasumsikan kalian sudah mengerjakan tahapan pertama, kita bisa langsung menggunakan sifat-sifat dan definisi yang kita miliki sebagai berikut:

<details close>
<summary> Click to see answer</summary>
$$
\begin{align*}
\sqrt[3]{a^6} \cdot \sqrt[4]{a^9} &= a^{\frac{6}{3}} \cdot a^{\frac{9}{4}}\\
&= a^2 \cdot a^{\frac{9}{4}}\\
&= a^2 \cdot a^{2\cdot\frac{9}{4}}\\
&= a^2 \cdot a^{\frac{9}{2}}\\
&= a^{2 + \frac{9}{2}}\\
&= a^{\frac{4}{2} + \frac{9}{2}}\\
&= a^{\frac{13}{2}}\\
&= \sqrt{a^{13}}\\
&= \sqrt{a^{2\cdot6 + 1}}\\
&= \sqrt{a^{12} \cdot a^1}\\
&= a^\frac{12}{2}\cdot \sqrt{a}\\
&= a^6\sqrt{a}
\end{align*}
$$
</details>

Setelah melihat kedua contoh soal tersebut, saya rasa kalian sudah siap untuk menyelesaikan ketiga soal berikut. Cobalah untuk kalian kerjakan

## Soal 1
Sederhanakanlah ekspresi berikut:

$$\left( \frac{4^x \cdot 2^{3x-1}}{8^{x-2}} \right)$$

Clue: Perhatikan bahwa 4, 2, dan 8 memiliki hubungan pangkat.

## Soal 2
Sederhanakanlah ekspresi berikut:

$$\left( \frac{5^{3x-1} \cdot 125^{2x+1}}{25^{4x} \cdot 2^{x+3}} \right)
$$

Clue: Perhatikan bahwa 5 dan 125 memiliki hubungan pangkat.

## Soal 3
Sederhanakanlah ekspresi berikut:

$$\left( \frac{6^{x+1} \cdot 3^{2x-1}}{9^{x+2}} \right)$$

Clue: Perhatikan bahwa 6, 3, dan 9 memiliki hubungan pangkat.

## Solusi
Berikut adalah solusi dari 3 soal yang diberikan diatas.

### Solusi Soal 1
Perhatikan bahwa disini $4=2^2$ dan $8=2^3$. Selain itu, cara kamu juga mungkin saja berbeda. Hal yang penting adalah hasilmu sama.

$$
\begin{align*}
\frac{4^x \cdot 2^{3x-1}}{8^{x-2}} &= \frac{2^{2x} \cdot 2^{3x-1}}{(2^3)^{x-2}} \\
&= \frac{2^{2x} \cdot 2^{3x-1}}{2^{3(x-2)}} \\
&= 2^{2x} \cdot 2^{3x-1-3(x-2)} \\
&= 2^{2x} \cdot 2^{3x-1-3x+6} \\
&= 2^{2x} \cdot 2^{5} \\
&= 2^{2x+5}
\end{align*}
$$

### Solusi Soal 2
Disini, kamu bisa menggunakan fakta bahwa $125=5^3$ dan $25=5^2$.

$$
\begin{align*}
\frac{5^{3x-1} \cdot 125^{2x+1}}{25^{4x} \cdot 2^{x+3}} &= \frac{5^{3x-1} \cdot (5^3)^{2x+1}}{(5^2)^{4x} \cdot 2^{x+3}} \\
&= \frac{5^{3x-1} \cdot 5^{6x+3}}{5^{8x} \cdot 2^{x+3}} \\
&= \frac{5^{3x-1+6x+3-8x}}{2^{x+3}} \\
&= \frac{5^{9x+2-8x}}{2^{x+3}} \\
&= \frac{5^{x+2}}{2^{x+3}}
\end{align*}
$$

Atau sebenarnya jika ingin lebih disederhanakan, bisa disederhanakan menjadi: $\frac{5^{x+2}}{2^{x+3}}=\left(\frac{5}{2}\right)^x\cdot\left(\frac{25}{8}\right)$., 

### Solusi Soal 3
Disini, kamu bisa menggunakan 2 fakta, yaitu $6=2\cdot 3$ dan $9=3^2$.

$$
\begin{align*}
\frac{6^{x+1} \cdot 3^{2x-1}}{9^{x+2}} &= \frac{6^{x+1} \cdot 3^{2x-1}}{(3^2)^{x+2}} \\
&= \frac{6^{x+1} \cdot 3^{2x-1}}{3^{2(x+2)}} \\
&= 6^{x+1} \cdot 3^{2x-1-2(x+2)} \\
&= 6^{x+1} \cdot 3^{2x-1-2x-4} \\
&= 6^{x+1} \cdot 3^{-5} \\
&= \frac{6^{x+1}}{3^5}\\
&= \frac{(2\cdot 3)^{x+1}}{3^5}\\
&= \frac{2^{x+1}\cdot 3^{x+1}}{3^5}\\
&= 2^{x+1}\cdot 3^{x+1-5}\\
&= 2^{x+1}\cdot 3^{x-4}
\end{align*}
$$

## Penutup
Selamat, kamu sudah menyelesaian ketiga bagian dari blog pembahasan tentang materi eksponen. Saya harap blog ini dapat membantumu untuk mempelajari hal baru. 

Oh iya, apakah kamu ingat motivasi awal kita tentang kenapa kita ingin belajar soal eksponen? Kita ingin menyelesaikan suatu soal kan. Sekarang dengan kemampuanmu, harusnya kamu sudah bisa menyelesaikan soal tersebut. Cobalah untuk menyelesaikan soal ini:

$$\frac{2^{50}}{20^5}\cdot \frac{3^{10}}{2^{25}}$$