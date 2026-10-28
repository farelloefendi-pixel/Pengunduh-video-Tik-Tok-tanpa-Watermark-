# Multi Platform Downloader (Jieshuo)

Ekstensi pembaca layar Jieshuo untuk mengunduh video, foto, dan audio dari TikTok, Instagram, dan YouTube, berbahasa Indonesia.

## Fitur
- TikTok: video, foto (slideshow), dan audio MP3. Sumber utama langsung dari TikTok, dengan beberapa layanan cadangan yang berpindah otomatis
- Instagram: video, foto, dan carousel dari postingan publik, termasuk tautan hasil bagikan
- YouTube: video MP4 atau audio MP3 dengan pilihan kualitas, dan konfirmasi sebelum mengunduh file besar
- Unduh banyak tautan sekaligus (TikTok dan Instagram), peringatan jika tautan sudah pernah diunduh, coba ulang yang gagal
- Lokasi unduhan bisa dipilih sendiri, di penyimpanan internal maupun kartu SD
- Pengaturan kualitas video dan audio: Tertinggi, Sedang, Terendah, atau Tanya setiap kali
- Daftar layanan diperbarui otomatis dari file `layanan.json` di repositori ini
- Cek pembaruan ekstensi dengan unduh otomatis file pembaruan
- Riwayat unduhan dengan aksi bagikan (satu atau banyak file), buka di pemutar, salin judul dan tautan, dan hapus
- Menu "Laporkan masalah" yang menyalin rincian teknis ke papan klip

## Lokasi hasil unduhan
Secara bawaan, hasil disimpan di folder `Multi Platform Downloader`, dipisah ke subfolder `TikTok`, `Instagram`, dan `YouTube`. Lewat menu "Lokasi unduhan", folder tujuan bisa diganti.

Jika Jieshuo diberi izin Akses semua file, folder bisa dipilih bebas di penyimpanan internal maupun kartu SD. Tanpa izin itu, pilihan terbatas pada folder publik di penyimpanan internal seperti Download, Movies, Music, Pictures, DCIM, dan Documents. Izin bisa diaktifkan lewat menu "Izin penyimpanan".

## Kualitas unduhan
Pengaturan kualitas berlaku berbeda di tiap platform:
- YouTube: mengikuti pilihan dari daftar kualitas yang tersedia
- TikTok: hanya dua tingkat. Tertinggi memakai HD jika tersedia, Sedang dan Terendah memakai versi standar
- Instagram: tidak ada pilihan kualitas

## Cara pasang
1. Unduh file `MULTI_PLATFORM_DOWNLOADER.ppk` dari repositori ini.
2. Impor ke Jieshuo lewat menu plugin.

## Catatan
Gunakan hanya untuk konten milik sendiri atau dengan izin pemiliknya. Mengunduh dan menyebarkan konten orang lain dapat melanggar ketentuan TikTok, Instagram, YouTube, dan hak cipta. Ekstensi memakai layanan pihak ketiga, jadi tautan yang diunduh dikirim ke layanan tersebut. Ekstensi tidak mengumpulkan data pengguna.

File `layanan.json` hanya berisi data (alamat dan petunjuk letak data), tidak pernah berisi kode yang dijalankan.

## Cara merilis pembaruan (untuk pengelola)
1. Unggah file `.ppk` versi baru ke folder utama repositori dengan nama yang sama.
2. Ubah `versi` dan `catatan` di bagian `ekstensi` pada `layanan.json`.
3. Pengguna akan diberi tahu otomatis dalam sehari, atau langsung lewat menu "Cek pembaruan ekstensi".
