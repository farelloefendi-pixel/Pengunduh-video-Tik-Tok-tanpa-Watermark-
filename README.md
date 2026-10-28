# Pengunduh TikTok Tanpa Watermark (Jieshuo)

Ekstensi pembaca layar Jieshuo untuk mengunduh video atau audio TikTok tanpa watermark, berbahasa Indonesia.

## Fitur
- Unduh video atau audio MP3, satu atau banyak tautan sekaligus
- Beberapa layanan cadangan dengan perpindahan otomatis
- Daftar layanan diperbarui otomatis dari file `layanan.json` di repositori ini
- Cek pembaruan ekstensi dengan unduh otomatis file pembaruan
- Riwayat unduhan dengan aksi bagikan (satu atau banyak file), buka di pemutar, salin judul dan tautan, dan hapus
- Peringatan jika tautan sudah pernah diunduh
- Menu "Laporkan masalah" yang menyalin rincian teknis ke papan klip
- Coba ulang unduhan yang gagal

## Lokasi hasil unduhan
Jika Jieshuo diberi izin Akses semua file, hasil disimpan di folder `PENGUNDUH TIKTOK TANPA WATERMARK INDONESIA` di penyimpanan internal. Tanpa izin itu, hasil disimpan di `Download/PENGUNDUH TIKTOK TANPA WATERMARK INDONESIA`. Izin bisa diaktifkan lewat menu "Izin penyimpanan".

## Cara pasang
1. Unduh file `.ppk` dari repositori ini.
2. Impor ke Jieshuo lewat menu plugin.

## Catatan
Gunakan hanya untuk video milik sendiri atau dengan izin kreator. Mengunduh dan menyebarkan konten orang lain dapat melanggar ketentuan TikTok dan hak cipta. Ekstensi memakai layanan pihak ketiga, jadi tautan yang diunduh dikirim ke layanan tersebut. Ekstensi tidak mengumpulkan data pengguna.

File `layanan.json` hanya berisi data (alamat dan petunjuk letak data), tidak pernah berisi kode yang dijalankan.

## Cara merilis pembaruan (untuk pengelola)
1. Unggah file `.ppk` versi baru ke folder utama repositori dengan nama yang sama, `PENGUNDUH_TIKTOK_TANPA_WATERMARK_INDONESIA.ppk`.
2. Ubah `versi` dan `catatan` di bagian `ekstensi` pada `layanan.json`.
3. Pengguna akan diberi tahu otomatis dalam sehari, atau langsung lewat menu "Cek pembaruan ekstensi".
