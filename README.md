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
