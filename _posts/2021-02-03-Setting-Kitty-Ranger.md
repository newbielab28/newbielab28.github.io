---
tags: linux terminal ranger
title: Menampilkan thumbnail pada ranger
image: ranger-kitty.jpg
excerpt_separator: <!--more-->
---
![ranger-kitty]({{site.baseurl}}/assets/img/ranger-kitty.jpg){:class="img-responsive"}

Cara setting ranger file manager pada Kitty. <!--more-->

Ranger adalah sebuah file manager berbasis konsol dengan VIM keybindings. Menyediakan tampilan minimalistik dengan konsep direktori hirarki.

Saya sarankan teman-teman menggunakan terminal emulator alacritty atau kitty yang sudah pernah saya coba sebelumnya dan berhasil. Jika belum punya silahkan mengikuti tutorial install kitty di [Install dan konfigurasi kitty terminal emulator](https://linoxide.com/kitty-terminal-emulator/).

## 1. Instalasi Ranger

> $ sudo apt install ranger

Setelah terinstall, ranger akan membuat sebuah direktori di `~/.config/ranger` . Untuk menyalin konfigurasi dasar ranger ke direktori tersebut ketikkan command ini di terminal.

> $ ranger --copy-config=all

## 2. Konfigurasi Ranger

Buka file konfigurasi ranger di `~/.config/ranger/rc.conf`, kemudian cari baris dan cocokkan dengan baris di bawah ini

> set preview_images true
>
> set preview_images_method w3m

Atau jika menggunakan terminal kitty emulator bisa menggunakan ini :

> set preview_images_method kitty

Terakhir, kita ketikkan `$ ranger` pada terminal dan arahkan ke file gambar/ video.

Berikut hasilnya.

![ranger-file-manager]({{site.baseurl}}/assets/img/ranger-kitty-tampil-gambar.png){:class="img-responsive"}

### Referensi
---
- [install kitty](https://linoxide.com/kitty-terminal-emulator/)



### Referensi
