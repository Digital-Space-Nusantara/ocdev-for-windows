# OCDev Tunnel for Windows

OCDev Tunnel adalah solusi *reverse proxy* yang aman dan tangguh untuk mengekspos server lokal Anda ke internet publik secara instan. Tanpa perlu konfigurasi port forwarding di router lokal (Bypass NAT & Firewall), lalu lintas Anda terenkripsi secara otomatis menggunakan End-to-End SSL/HTTPS.

Proyek ini merupakan *Windows Client* resmi dari **DSN Data Center** untuk layanan tunneling OCDev.

## Fitur Unggulan

- **Bypass NAT & Firewall**: Mengekspos port lokal ke publik tanpa modifikasi router.
- **End-to-End Encryption**: Koneksi aman dengan SSL otomatis.
- **Custom Subdomain**: Gunakan subdomain spesifik yang terdaftar di akun Anda (mis. `namakamu.tunnel.our-chat.web.id`).
- **Authtoken Security**: Otentikasi sesi tunnel terpusat dari dashboard OCDev.

## Persyaratan
- Sistem Operasi: Windows 10 / 11 (64-bit)
- Koneksi Internet

## Instalasi

1. Download file executable (`ocdev.exe`) versi terbaru dari halaman [Releases](https://github.com/Digital-Space-Nusantara/ocdev-for-windows/releases).
2. Pindahkan `ocdev.exe` ke direktori pilihan Anda.
3. (Opsional) Tambahkan path direktori tersebut ke *Environment Variables* Windows agar perintah `ocdev` dapat diakses dari direktori mana pun di Terminal.

## Cara Penggunaan

Buka **Command Prompt** atau **PowerShell**, lalu jalankan perintah berikut:

```powershell
# Format Perintah
ocdev tunnel <PORT_LOKAL> <SUBDOMAIN> --token <TOKEN_ANDA>

# Contoh
ocdev tunnel 3000 namakamu --token 1234567890abcdef
```

* Kunjungi [Dashboard OCDev Tunnel](https://tunnel.our-chat.web.id/dashboard/dsn-tunnel) (Sesuaikan dengan URL dashboard Anda) untuk mengklaim subdomain dan mendapatkan Authtoken.

## Panduan Bantuan

Bila Anda membutuhkan bantuan atau menemukan *bug*, silakan buat tiket di halaman [Issues](https://github.com/Digital-Space-Nusantara/ocdev-for-windows/issues).

---
Dikembangkan dengan ❤️ oleh [DSN Data Center](https://github.com/Digital-Space-Nusantara/)
