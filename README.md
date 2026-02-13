<p align=center>
<br>
<a href="#iOS"><img src="https://img.shields.io/badge/platform-iOS-black?logo=apple&logoColor=white"></a>
<a href="#iSH"><img src="https://img.shields.io/badge/shell-iSH-blue"></a>
<a href="#VLC"><img src="https://img.shields.io/badge/player-VLC-orange"></a>
<br>

<h1 align="center">ani-cli (iOS / iSH Edition)</h1>

<h3 align="center">
  Nonton Anime di iPhone/iPad lewat Terminal.
  <br>
  (Unofficial fork of <a href="https://github.com/pystardust/ani-cli">ani-cli</a> patched for iOS)
</h3>
</p>

---

## 📱 Tentang Project Ini
Ini adalah versi modifikasi dari `ani-cli` agar bisa berjalan lancar di **iOS** menggunakan **iSH Shell**. Script ini memaksa video untuk diputar langsung ke aplikasi **VLC for Mobile**, karena player bawaan iSH sering nge-lag atau tidak jalan.

## 📋 Persyaratan (Wajib)
Sebelum install, pastikan kamu sudah download 2 aplikasi ini di App Store:
1.  **[iSH Shell](https://apps.apple.com/us/app/ish-shell/id1436902243)** (Terminal Linux untuk iOS)
2.  **[VLC for Mobile](https://apps.apple.com/us/app/vlc-for-mobile/id650377962)** (Video Player)

## 🚀 Cara Install (Langkah demi Langkah)

Buka aplikasi **iSH Shell**, lalu ketik perintah di bawah ini satu per satu:

### 1. Update System & Install Dependencies
Kita perlu menginstall alat-alat dasar seperti git, curl, dan text processing tools.

```sh
apk update && apk upgrade
apk add git curl grep sed fzf ncurses aria2
```
### 2. Clone Script Ini
Download script yang sudah dimodifikasi dari repository ini.

```sh
git clone [https://github.com/abdillahagil5/ani-cli-ios.git](https://github.com/abdillahagil5/ani-cli-ios.git)
```
### 3. Pindahkan & Beri Izin Eksekusi
Pindahkan file script ke folder sistem agar bisa dipanggil dari mana saja.
```sh
# Masuk ke folder hasil download
cd ani-cli-ios

# Pindahkan file utama ke /usr/bin
cp ani-cli /usr/bin/ani-cli

# Beri izin agar file bisa dijalankan (executable)
chmod +x /usr/bin/ani-cli
```
# (Opsional) Hapus folder mentahan instalasi biar hemat memori
```sh
cd ..
rm -rf ani-cli-ios
```
### 🎬 Cara Pakai
Setelah sukses install, kamu tinggal ketik perintah ini di terminal iSH kapan saja:
```sh
ani-cli
```
##Panduan Navigasi:
1. Ketik Judul: Masukkan judul anime (misal: one piece).
2. Pilih Anime: Gunakan panah atas/bawah atau ketik nomor urutnya.
3. Pilih Episode: Ketik nomor episode yang mau ditonton.
4. Pilih Kualitas: Pilih resolusi (Best/1080p/720p).