# 📋 Sistem Absensi Digital & Laporan Wali Kelas (Kelas 10)

Aplikasi web ringan berbasis HTML, CSS, dan JavaScript untuk mencatat kehadiran harian siswa **Kelas 10** (11 murid) secara praktis serta menyusun laporan rekapitulasi bulanan resmi untuk wali kelas secara otomatis.

## ✨ Fitur Utama
* **Absensi Harian Otomatis:** Mencatat status kehadiran harian (**Hadir**, **Sakit**, **Izin**, **Alpa**) berdasarkan tanggal, dilengkapi tombol **Hadir Semua** dalam satu klik.
* **Rekapitulasi Bulanan Otomatis:** Menghitung total masing-masing status kehadiran dan persentase kehadiran (%) per siswa secara otomatis sesuai bulan dan tahun yang dipilih.
* **Generator Keterangan Wali Kelas:** Menyusun narasi evaluasi kehadiran kelas secara otomatis (rata-rata kehadiran kelas, daftar siswa hadir penuh 100%, serta rincian siswa yang sakit/izin/alpa).
* **Kolom Pengesahan Otomatis:** Dilengkapi input **Nama Wali Kelas** dan **Nama Sekretaris/Ketua Kelas** yang tersimpan otomatis pada bagian tanda tangan laporan.
* **Laporan WhatsApp & Salin Teks:** Mengirimkan rekap harian maupun laporan bulanan resmi langsung ke WhatsApp Wali Kelas atau menyalin teks laporan dalam satu klik.
* **Penyimpanan Lokal (`Local Storage`):** Seluruh data tersimpan langsung di browser perangkat tanpa memerlukan koneksi database eksternal.

## 🚀 Cara Menggunakan
1. Buka tautan website aplikasi melalui browser HP atau laptop.
2. Pada tab **Absen Harian**, pastikan tanggal sudah sesuai, lalu pilih status **H / S / I / A** untuk setiap siswa (atau tekan **Hadir Semua**).
3. Buka tab **Rekap & Laporan Wali Kelas** di akhir bulan untuk melihat persentase kehadiran.
4. Isi kolom **Nama Wali Kelas** dan **Nama Sekretaris/Ketua Kelas** (cukup diisi satu kali).
5. Klik **Kirim Laporan ke WA Wali Kelas** atau **Salin Teks Laporan** untuk membagikan hasil rekap.

## 🛠️ Teknologi yang Digunakan
* HTML5
* CSS3 (Responsive Mobile-First Design)
* Vanilla JavaScript (`LocalStorage API`)
