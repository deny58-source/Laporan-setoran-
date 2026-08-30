# Laporan Harian Setoran Gold Farming — EVO GAMING FH2

Aplikasi web statis (HTML + JS, tanpa backend) untuk mencatat setoran gold farming harian per karyawan, lengkap dengan nama game dan jam setoran otomatis, serta ekspor laporan ke WhatsApp.

## Cara Upload ke GitHub

1. Buat repository baru di GitHub (bisa publik atau privat).
2. Upload file `index.html` ini ke root repository (drag & drop lewat tombol **Add file → Upload files** di halaman GitHub, atau via `git push`).
3. Commit perubahan.

## Cara Mengaktifkan sebagai Website (GitHub Pages)

1. Buka repository → tab **Settings**.
2. Di sidebar kiri, klik **Pages**.
3. Pada bagian **Source**, pilih branch `main` (atau `master`) dan folder `/ (root)`.
4. Klik **Save**.
5. Tunggu 1–2 menit, lalu buka link yang muncul (formatnya `https://namauser.github.io/nama-repo/`).

## Catatan Penting

- Data (setoran, roster karyawan, nama game, jam) disimpan di **localStorage browser**, bukan di server/database. Artinya:
  - Data hanya tersimpan di browser & perangkat yang dipakai untuk mengisi.
  - Jika dibuka dari perangkat/browser lain, data akan kosong (mulai dari roster default).
  - Membersihkan cache/data browser akan menghapus data yang tersimpan.
- Cocok dipakai sebagai alat isi laporan harian pribadi/tim kecil, bukan sebagai database terpusat multi-user.
- Jika ke depannya perlu data tersimpan terpusat (bisa diakses banyak orang dari perangkat berbeda), aplikasi ini perlu ditambahkan backend/database — beri tahu saya jika perlu ini.
