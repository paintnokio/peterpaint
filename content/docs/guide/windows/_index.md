---
linkTitle: "Documentation Microsoft"
title: Petunjuk
---

👋 Halo! Selamat datang di dokumentasi Code Stack!

<!--more-->

## Mengkatifkan Windows dan Ms-Office

Aktivator Windows dan Office open-source dengan berbagai metode aktivasi termasuk HWID, Ohook, TSforge, KMS38, dan Online KMS, dilengkapi fitur troubleshooting lanjutan.

## Metode 1 
### Menggunakan Powerhell (Windows 8 dan yang lebih baru)

{{< callout emoji="ℹ️" >}}
1. Buka Powershell sebagai administrator caranya:
  * Tekan Logo Windows 🪟 + X Pada Keyboard
  * Pilih "Windows Powershell(Admin)
2. Jalankan Perintah Berikut:

   ```cmd
   irm https://get.activated.win | iex
   ```
   atau alternatif (akan dihentikan di masa mendatang)

   ```cmd
     irm https://massgrave.dev/get | iex
     ```
3. Pilih Metode Aktivasi
   * Tekan [ 1 ] untuk aktivasi windows ( HWID )
   * Tekan [ 2 ] untuk aktivasi ms-office ( Ohook )
4. Tunggu Proses selesai dengan menampilan "SUCCES" tek hijau
{{< /callout >}}

## Metode 2
### Manual (Windows Vista dan yang lebih baru)

{{% details title="Klik detail" closed="true" %}}

1. Unduh File Aktivasi
   * Pilih salah satu link di bawah ini:
      * [Download Akitivator 01](https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip)
      * [Download Aktivator 02](https://git.activated.win/massgrave/Microsoft-Activation-Scripts/archive/master.zip)

1. Extrak file ZIP yang di unduh
   * Pada folder hasil extraksi, cari folder bernama `All-In-One-Version`
2. Jalankan file `MAS_AIO.cmd`
   * klik kanan pilih 👉`Run as administrator`👈 **WAJIB**
3. Ikuti petunjuk di layar lcd anda

{{% /details %}}

## Jika Tidak Berhasil ❓

* Jika `tidak berhasil menjalan akitvasi metode 1, gunakan metode 2 diatas
* Jika ` Microsoft aktivasi script` terbuka dan menapikan error, ikuti langkah troubleshooting yang di tandai warna biru
* Jika maslah tetap ad, hubungi kami [disini](https://devcomp.fun/troubleshoot)

{{% details title="Catatan" %}}
* Perintah IRM di PowerShell mengunduh script dari URL tertentu, dan IEX menjalankannya
* Selalu periksa URL sebelum menjalankan perintah dan pastikan sumber terpercaya saat mengunduh file manual
* Waspadai malware yang menyamar sebagai MAS dengan mengubah URL di perintah IRM

{{% /details %}}

## Rilis Terbaru
Versi Terakhir - v3.4 (3-June-2025):

[Github](https://github.com/massgravel/Microsoft-Activation-Scripts) |
[Azura DevOps](https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts) |
[Self-hosted Git](https://git.activated.win/massgrave/Microsoft-Activation-Scripts)


## Fitur Utama
* **HWID** (Lisensi Digital): Aktivasi permanen windows
* **Ohook**: Aktivasi permanen microsoft office
* **Tsforge**: Aktivasi windows/ESU/Office
* **KMS38**: Aktivasi hingga tahun 2038
* **Online KMS**: Aktivasi windows/office selema 180 hari (dapat diperpanjang otomatis)
* Troubleshooting aktivasi lanjutan
* Foler $OEM$ untuk pra-aktivasi
* Ubah Edisi office
* Cek status windiws/office
* Tersedia dalam veriso all-in-one dan terpisah
* Opensource berbasih script batch
* Mini dekteksi antivirus

## Ringkasan Aktivasi

| Tipe Aktivasi | Produk Didukung | Masa Aktivasi | Butuh Internet? |
|--------------|----------------|--------------|----------------|
| HWID | Windows 10-11 | Permanen | Ya |
| Ohook | Office | Permanen | Tidak |
| TSforge | Windows/ESU/Office | Permanen | Tidak |
| KMS38 | Windows 10-11-Server | Hingga 2038 | Tidak |
| Online KMS | Windows/Office | 180 hari (dapat diperpanjang) | Ya |

Untuk detail lebih lanjut, lihat dokumentasi dan [tabel perbandingan](#).  
Untuk aktivasi produk tidak resmi seperti **Office di Mac**, lihat [di sini](#).

## Screenshot
{{< cards >}}
  {{< card
        link="#"
        title="Powershell step 01"
        subtitle="Pilih No.1 Untuk Aktivasi Windows"
        image="/images/screenshoot/MAS_AIO.png"
        imageStyle="object-fit:cover; aspect-ratio:16/9;"
  >}}
    {{< card
        link="#"
        title="Powershell step 02"
        subtitle="Tunggu Proses Sampai Tulisan Berwarna Hijau SUKSES"
        image="/images/screenshoot/MAS_HWID.png"
        imageStyle="object-fit:cover; aspect-ratio:16/9;"
  >}}
      {{< card
        link="#"
        title="Powershell step 03"
        subtitle="Pilih No.2 Untuk Aktivasi Microsoft Office"
        image="/images/screenshoot/MAS_AIO.png"
        imageStyle="object-fit:cover; aspect-ratio:16/9;"
  >}}
      {{< card
        link="#"
        title="Powershell step 04"
        subtitle="Tunggu Proses Sampai Tulisan Berwarna Hijau SUKSES"
        image="/images/screenshoot/MAS_Ohook.png"
        imageStyle="object-fit:cover; aspect-ratio:16/9;"
  >}}
  
{{< /cards >}}

{{< callout emoji="🌐">}}
  Sukses, selamat berkativitas kembali, salam sehat selalu.
{{< /callout >}}
