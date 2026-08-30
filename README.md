# Laporan Harian Setoran Gold Farming — EVO GAMING FH2

Aplikasi web statis  untuk mencatat setoran gold farming harian per karyawan, lengkap dengan nama game dan jam setoran otomatis, serta ekspor laporan ke WhatsApp.


## Catatan Penting

- Data (setoran, roster karyawan, nama game, jam) disimpan di **localStorage browser**, bukan di server/database. Artinya:
  - Data hanya tersimpan di browser & perangkat yang dipakai untuk mengisi.
  - Jika dibuka dari perangkat/browser lain, data akan kosong (mulai dari roster default).
  - Membersihkan cache/data browser akan menghapus data yang tersimpan.
- Cocok dipakai sebagai alat isi laporan harian pribadi/tim kecil, bukan sebagai database terpusat multi-user.
- Jika ke depannya perlu data tersimpan terpusat (bisa diakses banyak orang dari perangkat berbeda), aplikasi ini perlu ditambahkan backend/database — beri tahu saya jika perlu ini.
