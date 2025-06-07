---
title: "Mengatasi Masalah Lisensi AutoCAD"
---

### Gejala Umum
- Pesan error:  
  
  `"License check failed. Error [-15]"`  
  `"The license manager is not functioning or is improperly installed"`
  
- AutoCAD menutup sendiri setelah startup
- Tidak bisa aktivasi produk

### Penyebab Utama
1. Cache lisensi corrupt
2. Konflik dengan instalasi AutoCAD sebelumnya
3. Masalah jaringan (untuk lisensi jaringan)
4. Kesalahan aktivasi

### Solusi Langkah-demi-Langkah

#### 1. Reset Lisensi
1. Tutup AutoCAD
2. Buka **Command Prompt sebagai Administrator**
3. Jalankan perintah:
   
   ```cmd
   cd "C:\Program Files (x86)\Common Files\Autodesk Shared\AdskLicensing"
   ```
4. Eksekusi
   
   ```cmd
   uninstall.exe
   ```
5. Install ulang AdskLicensing dari folder:
   
   ```cmd
   AdskLicensing-installer.exe install --verbose
   ```

#### 2. Hapus File Lisensi Lama
1. Buka Folder:
   
   ```cmd
   C:\ProgramData\Autodesk\AdskLicensingService
   ```
2. Hapus semua file di folder tersebut
3. Restart komputer

#### 3. Untuk Lisensi Jaringan
1. Pastikan server lisensi aktif
2. Di AutoCAD, gunakan konfigurasi:
   
   ```cmd
   * Port: 27000@NameServer
   * Contoh: 27000@LicenseServer01
   ```
3. Aktivasi Offline
   Jika aktivasi online gagal:
   1. Pilih **Aktivasi Offline**
   2. Generate request code
   3. Kunjungi:
   ```cmd
   autode.sk/register
   ```
   4. Masukan request code untuk mendapatkan activation code

### Link Resmi Autodesk

* [Dokumen Dukungan Lisensi](#)
* [Autodesk License Removal Tool](#)
   