# Random Credit Card Number Generator

[![Lisensi: MIT](https://img.shields.io/badge/Lisensi-MIT-kuning.svg)](https://opensource.org/licenses/MIT)
![Platform: Windows](https://img.shields.io/badge/Platform-Windows-biru)
![Offline](https://img.shields.io/badge/Status-Offline-hijau)

Generator nomor kartu kredit acak yang profesional, aman, dan berjalan offline untuk keperluan demo dan pengujian. Aplikasi ini menghasilkan data kartu kredit yang terlihat nyata tetapi **sepenuhnya palsu** untuk skenario edukasi, pengembangan, dan pengujian.

> **⚠️ PERINGATAN PENTING**
> Software ini menghasilkan nomor kartu kredit **palsu dan tidak berfungsi** untuk keperluan demonstrasi saja. Semua data yang dihasilkan benar-benar acak dan tidak terhubung dengan institusi keuangan nyata. Alat ini **TIDAK BOLEH** digunakan untuk aktivitas ilegal atau upaya penipuan.

## ✨ Fitur Unggulan

- **🔒 100% Berjalan Offline** - Tidak membutuhkan koneksi internet, sepenuhnya privat
- **🌍 Dukungan Multi-Negara** - Saat ini mendukung Indonesia, Amerika, Inggris, dan India
- **🔄 Validasi Algoritma Luhn** - Menghasilkan nomor kartu yang valid secara matematis tetapi palsu
- **📊 Informasi Kartu Lengkap** - Generasi data komprehensif termasuk:
  - BIN/IIN (Bank Identification Number)
  - Tanggal Kadaluarsa (Bulan/Tahun)
  - Kode CVV
  - Nama Pemegang Kartu
  - Jaringan Kartu (Visa, MasterCard, dll.)
  - Tipe Kartu (Kredit/Debit)
  - Kategori Kartu (Standard/Gold/Platinum)
  - Bank Penerbit
- **💾 Kemampuan Ekspor** - Simpan data yang dihasilkan ke format CSV/JSON
- **📋 Salin Satu Klik** - Salin detail kartu individu ke clipboard
- **🎯 Generasi Batch** - Hasilkan hingga 99.999 kartu sekaligus

## 🚀 Memulai Cepat

### Prasyarat Sistem
- Windows 10/11 (64-bit)
- .NET Framework 4.7.2 atau lebih tinggi
- Minimal 100MB ruang disk kosong

### Instalasi

1. **Unduh Aplikasi:**
   - Kunjungi bagian [Releases](https://github.com/MichaelJorky/Random-Credit-Card-Number-Generator/releases)
   - Unduh file `.zip` terbaru
   - Ekstrak isinya ke lokasi yang diinginkan

2. **Jalankan Aplikasi:**
   - Buka folder hasil ekstraksi
   - Klik dua kali `Credit.Card.Generator.exe`
   - Tidak perlu instalasi - aplikasi portable!

## 📖 Cara Penggunaan

### Langkah 1: Atur Parameter Generasi
- **Jumlah yang Dihasilkan**: Masukkan jumlah kartu yang akan dibuat (1 sampai 99.999)
- **Pilih Negara**: Pilih dari negara yang tersedia (Indonesia, Amerika, Inggris, India)

### Langkah 2: Hasilkan Kartu
- Klik tombol **"Generate"** untuk membuat data kartu palsu
- Lihat hasilnya di tabel yang tersedia

### Langkah 3: Kelola Data yang Dihasilkan
- **Salin Kartu Individu**: Klik tombol **"Copy"** di sebelah kartu dalam tabel
- **Simpan Semua Data**: Klik **"Save"** untuk mengekspor semua kartu ke file
- Format ekspor yang didukung: CSV, JSON, TXT

### Kolom Tabel Data
Tabel yang dihasilkan mencakup informasi berikut:

| Kolom | Deskripsi |
|--------|-------------|
| **No** | Nomor urut |
| **BIN/IIN** | Bank Identification Number (6-8 digit) |
| **Month** | Bulan kadaluarsa |
| **Year** | Tahun kadaluarsa |
| **CVV** | Card Verification Value |
| **Holder Name** | Nama pemegang kartu yang dihasilkan |
| **Network** | Jaringan kartu (Visa, MasterCard, dll.) |
| **Card Type** | Kredit atau Debit |
| **Card Category** | Standard, Gold, Platinum |
| **Issuer** | Bank/Institusi keuangan penerbit |

## 🔧 Detail Teknis

### Validasi BIN/IIN
- Menggunakan **algoritma Luhn** untuk membuat nomor yang valid secara matematis
- Rentang BIN berdasarkan informasi publik dari jaringan kartu
- **Tidak ada validasi real-time** terhadap bank atau processor pembayaran nyata

### Data Spesifik Negara
Setiap negara mencakup:
- Nama bank dan penerbit spesifik wilayah
- Pola generasi nama
- Rentang BIN umum
- Tipe dan kategori kartu lokal

### Fitur Keamanan
- **Tanpa akses internet** - semua data dihasilkan secara lokal
- **Tidak mengumpulkan data pribadi** - semua nama dihasilkan secara acak
- **Tidak menyimpan data yang dihasilkan** - kecuali disimpan secara eksplisit oleh pengguna
- **Tidak terhubung ke sistem keuangan**

## ⚠️ Catatan Penting

1. **Hanya untuk Edukasi**: Alat ini dirancang untuk pengujian software, keperluan edukasi, dan skenario demonstrasi.
2. **Bukan Kartu Nyata**: Nomor yang dihasilkan tidak akan berfungsi untuk transaksi sebenarnya.
3. **Kepatuhan Hukum**: Pengguna bertanggung jawab untuk mematuhi hukum setempat terkait data keuangan.
4. **Tanpa Garansi**: Gunakan dengan risiko sendiri. Pengembang tidak bertanggung jawab atas penyalahgunaan.

## 🌟 Fitur yang Direncanakan

- [ ] Dukungan negara tambahan
- [ ] Spesifikasi rentang BIN kustom
- [ ] Kustomisasi ekspor massal
- [ ] Versi antarmuka baris perintah
- [ ] Jaringan kartu lebih banyak (American Express, Discover, dll.)
- [ ] Opsi pemformatan lanjutan

## 🤝 Berkontribusi

Kami menerima kontribusi! Silakan ajukan Pull Request. Untuk perubahan besar, buka issue terlebih dahulu untuk mendiskusikan perubahan yang diinginkan.

## 📄 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail.

## 💖 Dukung Proyek Ini

Jika Anda merasa alat ini berguna dan ingin mendukung pengembangannya:

[![Donasi via Saweria](https://img.shields.io/badge/Donasi-Saweria-orange)](https://saweria.co/teknoxpert)

Dukungan Anda membantu pemeliharaan dan pengembangan proyek ini!

## 🐛 Melaporkan Masalah

Menemukan bug atau memiliki permintaan fitur? Silakan [buka issue](https://github.com/MichaelJorky/Random-Credit-Card-Number-Generator/issues) di GitHub.

---

**Penafian**: Software ini HANYA untuk KEPERLUAN PENGUJIAN DAN EDUKASI YANG SAH. Pengembang tidak bertanggung jawab dan tidak bertanggung jawab atas penyalahgunaan atau kerusakan yang disebabkan oleh program ini. Selalu pastikan Anda memiliki izin untuk menguji sistem dan patuhi semua hukum yang berlaku.
