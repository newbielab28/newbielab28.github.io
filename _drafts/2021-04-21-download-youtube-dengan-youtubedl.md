---
image: linux-logo-pinguin.jpeg
title: Download youtube dengan youtube-dl
excerpt_separator: <!--more-->
tags: aplikasi linux terminalBased
---

Dengan youtube-dl, kita bisa mendownload video dari youtube atau tempat lainnya menggunakan command line / terminal.

### Instalasi
---
Untuk pengguna UNIX (Linux & MACos)

- Download file yang di butuhkan & buat file tersebut menjadi excutable

> `$` `sudo wget https://yt-dl.org/downloads/latest/youtube-dl -O /usr/local/bin/youtube-dl`
>
> `$` `sudo chmod a+rx /usr/local/bin/youtube-dl`

### Cara Download Video
---
1. Copy link video youtube yang diinginkan
2. Buka Command Line dan ketikkan `youtube-dl`

`$ youtube-dl https://www.youtube.com/watch?v=pf_StalkSwM`

![Youtube-dl](/assets/img/ytdl-pict/terminal-youtubedl.png)

Otomatis akan mendownload video dengan kualitas terbaik yang tersedia.

### Memilih format video tertentu
---
Cek format video yang tersedia dengan perintah dibawah ini :

`$` `youtube-dl -F https://www.youtube.com/watch?v=pf_StalkSwM`

![Youtube-dl](/assets/img/ytdl-pict/ytdl-cek-format.png)

Download video dengan memilih format yang tersedia pada kolom format, misal saya ingin mendownload video dengan kualitas 360p maka saya tambahkan 18 (lihat tabel format).

`$` `youtube-dl -f 18 https://www.youtube.com/watch?v=pf_StalkSwM`

![Youtube-dl](/assets/img/ytdl-pict/ytdl-download-format.png)

### Download video dengan format audio / mp3
---
Disini akan dicontohkan convert video menjadi format mp3 menggunakan FFmpeg.


`$` `youtube-dl -x --audio-format mp3 --prefer-ffmpeg https://www.youtube.com/watch?v=wkBBN0ygI8c`

![Youtube-dl](/assets/img/ytdl-pict/ytdl-mp3.png)

References:
----
[youtube-dl](https://github.com/ytdl-org/youtube-dl)
