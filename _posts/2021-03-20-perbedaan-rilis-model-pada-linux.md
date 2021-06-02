---
tags: linux
title: Fixed vs Rolling Release
image: linux-rilis-model-edt.jpg
excerpt_separator: <!--more-->
---
![Linux Release Model]({{site.baseurl}}/assets/img/linux-rilis-model-edt.jpg){:class="img-responsive"}

Perbedaan model rilis pada linux. <!--more-->

Setiap distribusi linux menggunakan sebuah manajemen paket aplikasi yang berfungsi untuk install, update, dan hapus software aplikasi yang terpasang pada sistem operasi. Di dunia linux terdapat tiga model rilis yakni,

## 1. Stable Release
Pada stable / fixed rilis, hanya update patch security yang dilakukan secara berkala. Sementara penambahan software baru atau update-nya dilakukan bersamaan dengan di rilisnya versi OS terbaru dalam jadwal tertentu (Fixed), biasanya 6 bulan atau 1 tahun.

Stable/fixed rilis sangat direkomendasikan bagi pengguna linux pemula dikarenakan OS yang menggunakan model rilis ini bisa langsung di gunakan setelah proses instalasi selesai.

Contoh : Ubuntu, Mint, Debian, Fedora

## 2. Rolling Release
Setiap software aplikasi selalu di update sesaat setelah developer merilisnya. Dengan menggunakan model rolling, kita selalu mendapatkan versi terbaru dari sebuah software. Pilihan tepat jika kita menginginkan software terupdate. Karena rolling rilis di update berkala, maka tidak diperlukan re-install OS setiap 6 bulan atau 1 tahun. Cukup selalu lakukan update maka kita akan selalu mendapatkan versi OS & software yang terbarukan.

Namun, menggunakan model rolling release terkadang mendapat error / masalah setelah update karena alasan kompatibilitas software dengan OS.

Contoh : Arch, Manjaro

## 3. Semi Rolling
Model rilis ini hanya aplikasi pihak ketiga & security saja yang update secara rolling. Sementara untuk sistem inti OS menggunakan di update menggunakan model rilis stable/fixed sesuai jadwal rilis OS tersebut.

Sangat cocok jika kita masih mempertimbangkan soal stabilitas system core OS, sekaligus ingin mendapatkan update terbaru dari aplikasi pihak ketiga.

Contoh : Chakra Linux, MX Linux

### Referensi
---
- [average-linux-user](https://averagelinuxuser.com/rolling-vs-fixed-linux-release/)
