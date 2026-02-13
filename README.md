 <p align=center>
<br>
<a href="#iOS"><img src="https://img.shields.io/badge/os-ios-black?logo=apple&logoColor=white"></a>
<a href="#iSH"><img src="https://img.shields.io/badge/shell-iSH-blue"></a>
<a href="#VLC"><img src="https://img.shields.io/badge/player-VLC-orange"></a>
<br>

<h1 align="center">ani-cli (iOS Edition)</h1>

<h3 align="center">
  Unofficial fork of <a href="https://github.com/pystardust/ani-cli">ani-cli</a> patched for iOS devices.
  <br>
  Watch anime directly from your iPhone/iPad terminal using iSH and VLC.
</h3>
</p>

---

## 🍎 Mengapa Fork Ini? (Why this fork?)

Versi original `ani-cli` sering mengalami kendala saat dijalankan di **iSH Shell** (iOS), terutama pada bagian pemutaran video (player). Fork ini telah dimodifikasi untuk:
1.  **Integrasi VLC Mobile:** Memaksa script membuka link video langsung ke aplikasi **VLC for Mobile** menggunakan protokol `vlc-x-callback://`.
2.  **Optimasi iSH:** Disesuaikan dengan lingkungan Alpine Linux yang berjalan di iSH.

## 📋 Persyaratan (Requirements)

Sebelum menginstall, pastikan kamu sudah menginstall 2 aplikasi ini dari App Store:
1.  **[iSH Shell](https://apps.apple.com/us/app/ish-shell/id1436902243)** (Terminal Linux untuk iOS)
2.  **[VLC for Mobile](https://apps.apple.com/us/app/vlc-for-mobile/id650377962)** (Video Player)

## 🚀 Cara Install (Installation)

Buka aplikasi **iSH Shell**, lalu ketik perintah berikut baris per baris:

### 1. Update Package Manager
```sh
apk update && apk upgrade
