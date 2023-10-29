---
title: "Persamaan Kuardrat"
author: Darrel
date: 2023-10-28 21:45:30 +0700
categories: [SMP, Matematika]
tags: [persamaan kuardrat]
math: True
---

## Motivasi
Mencari nilai minimum dan maksimum merupakan hal yang penting sekali di dunia nyata. Misalnya, kita ingin mencari ketinggian maksimal sebuah bola jika kita lemparkan. Hal ini bisa kita analisis untuk semua olahraga. Misalkan olahraga bola basket, tenis meja, sepak bola, bulutangkis, dan banyak olahraga lain yang melibatkan bola yang dilemparkan.

Selain itu, jika kamu menyukai bermain _game_ tembak-tembakan, apakah kamu sadar bahwa sebagian game mensimulasikan dunia nyata dengan cara membuat peluru pada beberapa _game_ bergerak secara parabolik? Hal ini juga merupakan fungsi kuardrat!

## Prasyarat
Tidak ada prasyarat untuk pelajaran ini selain kamu yang menghafal perkalian. Hal ini sangat penting agar kamu bisa mengerti cara memfaktorkan persamaan persamaan kuardrat (jika kamu tidak mengerti pernyataan ini, abaikan saja). 

## Definisi
Persamaan kuardrat adalah persamaan yang berbentuk sebagai berikut:

$$
ax^2+bx+c=0
$$

Dimana a, b, dan c adalah bilangan ril.

Beberapa contoh persamaan kuardrat adalah sebagai berikut:
* $-x^2+2x-3=0$
* $2x^2-3x+2=0$
* $1.2x^2-3.2x-\frac{1243}{635}=0$
* $-\pi^2x^2-e^x+20=0$
* $x^2=0$

> Coba kamu gunakan _graphic calculator_ untuk menggambarkan persamaan-persamaan diatas. Kamu bisa menggunakan [desmos](https://www.desmos.com/calculator) untuk melakukan eksplorasi secara mandiri. Tetapi, kamu tidak perlu menuliskan `=0` pada desmos.
{: .prompt-tip }

## Sesuatu yang Menarik?
Apakah kamu sudah melihat grafik yang ada dengan menggunakan desmos? Saya harap sudah. 

Jika kamu perhatikan, grafik-grafik yang ada diatas dapat membentuk salah satu dari 2 kemungkinan grafik kuardrat yang mungkin muncul, yaitu grafik senyum dan grafik cemberut. Pada dasarnya, grafik senyum merupakan grafik yang turun kemudian naik (jika dilihat dari kiri ke kanan) sedangkan grafik terbalik merupakan grafik yang naik kemudian turun (jika dilihat juga dari kiri ke kanan).

Selain itu, kamu juga bisa melihat bahwa jika grafik kuardrat memiliki 3 kemungkinan, yaitu memotong sumbu x, menyentuh sumbu x (matematikawan atau gurumu mungkin menyebut ini sebagai menyinggung sumbu x), dan tidak menyentuh sumbu x.

## Mencari Akar?
Mencari akar pada persamaan kuardrat merupakan salah satu hal penting yang akan dibahas pada bagian ini. Hal ini penting dalam contoh aplikasi pada dunia olahraga yang tadi disebutkan pada bagian motivasi karena dengan mencari akar kita dapat mencari jarak "penerbangan" bola. Misalnya dalam permainan sepak bola, kita dapat mencari tau jarak bola terbang dari ditendang dan bagaimana dia akan mendarat.

Solusi umum untuk persamaan kuardrat adalah sebagai berikut:

$$
x_{1,2}=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$


Rumus tersebut dapat diturunkan dengan cara yang tidak terlalu sulit, tetapi jika kamu ingin mencarinya, ada banyak referensi lain di internet yang membahasnya. Pada blog ini, kita hanya akan menggunakan rumus tersebut.

## Contoh 1
Mari kita cari akar untuk persamaan $x^2+3x+2=0$.

Jika kita lihat, bentuk $ax^2+bx+c=0$ mirip dengan $x^2+3x+2=0$ dan bisa kita lihat bahwa $a=1$, $b=3$, dan $c=2$. Kemudian informasi ini bisa kita langsung masukkan ke rumus diatas.

$$
\begin{align*}
x_{1,2}=\frac{-3\pm\sqrt{3^2-4(1)(2)}}{2(1)} &=\frac{-3\pm\sqrt{9-8}}{2}\\
& =\frac{-3\pm\sqrt{1}}{2}\\
& =\frac{-3\pm 1}{2}\\
\end{align*}
$$

Lalu mari kita bagi untuk 2 kasus, yaitu kasus tambah dan kasus kurang. Misalkan $x_1$ adalah kasus tambah:

$$
x_1=\frac{-3+1}{2}=\frac{-2}{2}=-1
$$

Kemudian, mari kita kerjakan untuk kasus kurang:

$$
x_2=\frac{-3-1}{2}=\frac{-4}{2}=-2
$$

Jadi solusinya adalah -1 dan -2. Dalam kata lain, kita bisa juga menyatakan solusinya sebagai himpunan solusi yaitu {-1, -2}.

Pada dasarnya, kamu bisa semua persamaan kuardrat dengan rumus diatas. Tetapi tidak dapat dipungkiri bahwa rumus diatas lumayan _ribet_ untuk dilakukan. Terkadang, rumus tersebut juga terlalu _overkill_ untuk persamaan yang bisa kita "tebak" solusinya. Ini adalah cara lain untuk mencari solusi persamaan kuardrat.

## Cara Lain
Hal yang perlu dicatat adalah cara lain ini tidak selalu bisa bekerja karena bisa saja akar persamaanmu merupakan pecahan atau solusi-solusi lain yang angkanya "tidak enak". Oleh karena itu, saya menyebut ini sebagai cara lain.

Mari kita coba kerjakan soal yang sama yaitu mencari akar-akar persamaan $x^2+3x+2=0$.

Berikut adalah tahapannya:

1. Perhatikan 2. 2 adalah bagian $c$ pada $ax^2+bx+c=0$
2. Lihatlah apa yang menjadi faktor-faktor dari c. Dalam kasus ini, faktor dari 2 hanyalah 2 dan 1.
3. Perhatikan jika pasangan faktor yang ada jika dijumlahkan menjadi b. Dalam kasus ini, kita ingin mengetahui apakah 2 dan 1 jika dijumlahkan menjadi b, yaitu 3. Ternyata benar bahwa 2 dan 1 jika dijumlahkan menjadi 3.
4. Jika ada, maka pasangan tersebut adalah faktor. Jadi kita bisa menuliskan 2 dan 1 menjadi seperti berikut

$$
\begin{align*}
x^2+3x+2&=0\\
(x+2)(x+1)&=0
\end{align*}
$$

Perhatikan bahwa persamaan $ab=0$ berarti $a=0$ atau $b=0$. Hal ini sama juga dengan persoalan diatas, solusinya adalah $x+2=0$ atau $x+1=0$. Hal ini berarti solusinya adalah $x=-2$ atau $x=-1$. Perhatikan juga bahwa solusinya sama dengan cara awal kita tadi.