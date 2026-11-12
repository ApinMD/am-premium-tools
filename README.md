<div align="center">

# 🔥 Alight Motion Premium Injector

*Script Python interaktif untuk menginjeksi paket langganan Premium (Annual) pada akun Alight Motion menggunakan metode otentikasi Firebase.*

</div>

---

## ✨ Fitur Utama
- 🖥️ **Secure Login Page**: Halaman akses masuk eksklusif layar penuh bergaya *desktop* menggunakan Textual.
- 🎨 **Modern CLI**: Tampilan panel, animasi loading, dan menu navigasi panah yang cantik menggunakan Rich & Questionary.
- 🔄 **Auto Bypass Limit**: Dilengkapi delay pintar dan loop konfirmasi otomatis jika server menolak pengiriman link otentikasi.
- 🛡️ **IP Spoofing**: Generator header IP acak (`x-forwarded-for`, `x-real-ip`, dll) di setiap sesi untuk meminimalisir deteksi/rate-limit.

---

## 📱 Persiapan (Penting!)
Script ini dirancang khusus untuk dijalankan di **Termux** pada OS Android dan **linux**.

> ⚠️ **PERHATIAN:** Jangan menggunakan Termux dari Google Play Store karena versinya sudah usang (deprecated) dan akan menghasilkan banyak error saat menginstal package Python.

1. Hapus aplikasi Termux versi Play Store (jika kamu masih menggunakannya).
2. Download Termux versi terbaru yang resmi melalui F-Droid: **[Klik di sini untuk download Termux F-Droid](https://f-droid.org/repo/com.termux_1022.apk)**.
3. Install APK Termux yang baru saja di-download.

---

## 🛠️ Cara Install & Penggunaan

Buka aplikasi Termux kamu, lalu jalankan baris perintah di bawah ini secara berurutan (satu per satu):

**1. Update & Upgrade package Termux**
```bash
pkg update -y && pkg upgrade -y
termux-setup-storage
termux-change-repo
pkg install git -y
pkg install pip -y
pkg install python -y
pip install textual questionary rich requests
git clone https://github.com/ApinMD/am-premium-tools.git
cd am-premium-tools
python ampremium.py
```

<div align="center">

# ✦ Halo, aku Apin! ✦

### 🎓 Mahasiswa · 🐍 Python · 🌙 Lua

*Masih belajar, terus mencoba, dan pelan-pelan berkembang.*

<br>

[![YouTube](https://img.shields.io/badge/YouTube-Kunjungi%20Channel-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@apinyamada?si=-BuRQqO12Cgws0In)
[![WhatsApp Channel](https://img.shields.io/badge/WhatsApp-Ikuti%20Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://whatsapp.com/channel/0029VbDp6F9BPzjcr9n0qi1z)

</div>
