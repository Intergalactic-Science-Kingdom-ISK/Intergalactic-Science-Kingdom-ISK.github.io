---
title: "Getting Started: Bagian Tiga"
author: Darrel
date: 2023-10-23 22:36:30 +0700
categories: [Blogging, Tutorial]
pin: true
tags: [getting started]
---

## Tutorial Dengan Video
Jika kamu lebih nyaman melihat tutorial bagian ketiga ini dengan video, kamu bisa melakukannya dengan menonton video ini:

{% include embed/{youtube}.html id='{sh_epdIUWes}' %}

<!-- [ini](https://youtu.be/sh_epdIUWes). -->

## Prasyarat

Kami harap kamu sudah melihat tutorial sebelumnya yang telah kami buat. Blognya terletak pada link [ini]. Kamu perlu membaca blog sebelumnya untuk mempersiapkan perangkatmu dan dirimu untuk menjadi seorang _blogger_ sejati :D

Blog tersebut penting untuk kamu baca maupun tonton karena maupun blog tersebut mencakup beberapa hal berikut:
* Ruby
* Jekyll
* Masuk kedalam Github Organization Intergalactic Science Kingdom
* Dan melakukan _`clone`_ agar dokumen-dokumen pada github ada pada _`local machine`_ dimana kamu bekerja

## Membuat Blog Pertamamu

Mungkin hal inilah yang menjadi alasanmu ingin memulai semua tutorial ini, untuk sampai ke saat ini, saat dimana kamu akan menulis blogmu. Sekarang, inilah kesempatanmu untuk membuat _blog_ pertamamu. Tetapi sebelum itu, pastikan kamu sudah memiliki bahan tulisan yang ingin kamu tulis.

### Membuat File Markdown
Untuk membuat sebuah blog, kamu perlu membuat sebuah `file markdown` pada folder `_posts`. Kesepakatan yang akan kita gunakan untuk menamai file yang barusan kamu buat adalah `tahun-bulan-tanggal-judul-blog-kamu.md`. Hal ini sangat penting untuk diingat untuk mencegah hal-hal yang tidak diinginkan

### Membuat Front Matter
Setelah kamu membuat file markdown tadi, kamu perlu membuat `Front Matter`. Front Matter pada dasarnya adalah bagian paling atas dari file markdown yang telah kamu buat tadi. Kamu bisa membuatnya dengan format sebagai berikut:

```yaml
---
title: Judul Tulisan Kamu
author: Nama
date: YYYY-MM-DD HH:MM:SS +0700
categories: [Kategori, Subkategori]
pin: true
tags: [tag1, tag2, tag3]
---
```

#### Pertama Kali Menulis Blog?
Jika ini adalah kali pertamamu menulis blog, kamu perlu menambahkan namamu sebagai `author` bukan? Kamu bisa menambahkan namamu di sebuah file yang bernama `authors.yml` yang terletak di folder `_data`. Disana, kamu bisa menambahkan namamu sebagai berikut:

```yaml
Nama:
  name: Nama lengkap kamu
  url: url-yang-ingin-kamu-letakkan
```

Perhatikan bahwa pada blog ini, **kami tidak memaksa kamu untuk menggunakan nama asli kamu**, tetapi jika kamu ingin merubahnya menjadi nama asli maupun nama samaranmu, kamu bisa melakukannya dengan mudah pada `_data/authors.yml` dan semua bagian namamu yang terletak pada blog akan tergantikan secara otomatis. Selain itu **kamu juga bisa meletakkan media sosialmu pada url** jika kamu mau, misalkan instagram, twitter, facebook, atau bahkan githubmu sendiri.

### Menulis Tulisanmu
Selanjutnya, kamu bisa langsung menuliskan apa yang ingin kamu tuliskan pada blog ini. Kamu bisa melihat _cheatsheet_ pada [dokumentasi Chirpy]('https://chirpy.cotes.page/posts/write-a-new-post/#code-block'). Selamat menulis, kami harap kamu bisa menghasilkan tulisan-tulisan berkualitas yang dapat dibaca oleh banyak member ISK yang lain.

### Melihat Hasil Tulisanmu
Jika kamu ingin melihat hasil tulisanmu, kamu bisa menuliskan `jekyll serve` pada terminalmu. Kemudian, kamu bisa melakukan `CTRL+Klik Kiri` pada bagian `server adress`. Pada kasus saya, `http://127.0.0.1:4000/` (perhatikan bahwa mungkin pada kasusmu berbeda). Perhatikan juga bahwa jika kamu sedang menulis file markdown, kamu bisa langsung melakukan refresh browser untuk melihat tampilan blog yang paling baru yang kamu buat. Jika kamu sedang menyunting (_mengedit_) file yang memiliki ekstensi `.yml` kamu perlu menghentikan web browser milikmu untuk menampilkan hasil tulisanmu (baca tutorial bagian `Menghentikan Melihat Hasil Tulisanmu`) kemudian melakukan `jekyll server` kembali (pada dasarnya `Ctrl+C` kemudian `jekyll serve`).

### Menghentikan Melihat Hasil Tulisanmu
Untuk menghentikan melihat hasil tulisan yang telah kamu buat, kamu bisa melakukan `Ctrl+C` untuk menghentikan browser yang kamu miliki untuk menampilkan hasil blog yang kamu buat. 

### 4 Mantra git: Pull, Add, Commit, Push
Istilah `4 GIT MANTRAS: pull, add, commit, push` merupakan istilah yang sering dosen saya gunakan pada website salah satu mata kuliah kami yaitu [Operating System]('https://os.vlsm.org/'). Hal-hal merupakan tahapan yang perlu dilakukan untuk melakukan `deploy` terhadap blog yang barusan kamu buat. 

1. Pada terminal `editor` yang kamu miliki ketikkan git pull pada direktori tempat blog ini berada pada `local machine` milikmu
2. Kemudian ketikkan `git pull`. Hal ini adalah untuk 'menarik' pembaharuan yang telah orang yang _push_pada github. Ini dilakukan supaya _file_ pada _local machine_ merupakan file yang paling baru
3. Lakukan `git add .` **jangan lupakan titik**. Add pada dasarnya adalah untuk menambahkan perubahan-perubahan apa saja yang telah kamu buat. 
4. Lakukan `git commit -m "commit message yang ingin kamu tuliskan"`. _Commit_ (layaknya komitmen pada sebuah pernikahan :D) merupakan saat-saat dimana kamu sudah siap. Dalam kasus ini, kamu sudah benar-benar siap untuk 'mengunggah' perubahan yang telah kamu buat pada blog. **Hanya lakukan commit jika kamu sudah siap melakukan perubahan**. _Commit message_ merupakan pesan yang ingin kamu tuliskan agar perubahanmu dilihat oleh programmer lain. **Tolong untuk melakukan commit message yang jelas**, karena jika tidak kamu akan mendapatkan surat cinta dari saya :3
5. Terakhir, lakukan `git push -u origin main`. Hal tersebut kita lakukan untuk mendorong perubahan kita agar siap di-_deploy_. Lakukan saja perintah tersebut jika kamu tidak mengerti, tetapi **jika kamu adalah seorang programmer, perhatikan bahwa _branch_ yang kita gunakan adalah `main`**. 
6. Tunggu beberapa saat. Jika tidak terjadi _error_ pada proses `deployment` maka blog yang kamu barusan buat harusnya sudah dapat terlihat pada website blog ISK. Selamat, blog yang kamu buat sudah _public_.

## Penutup
Selamat, kamu sudah mengunggah hasil tulisanmu pada blog ISK. Selanjutnya pada bagian penutup ini saya akan menjelaskan beberapa hal yang mungkin perlu dijelaskan lebih dalam, yaitu istilah local machine dan deploy. `Local machine` adalah laptop maupun komputer dimana kamu sedang mengerjakan (atau merencanakan) blog ini. Pada dasarnya `Local machine` adalah tempat dimana hanya kamu yang dapat melihat website ini ketika belum di-_deploy_. Deployment (atau proses deploy) pada dasarnya adalah membuat website yang kamu miliki pada `local machine` yang kamu miliki ke internet. Hal ini penting agar semua orang dapat melihat website yang telah kamu buat.