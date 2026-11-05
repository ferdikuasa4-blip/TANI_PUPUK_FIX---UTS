# TANI PUPUK - Aplikasi UTS Pengembangan Web

Aplikasi pengelolaan dan pemesanan pupuk berbasis PHP Native, PDO, MySQL, dan Bootstrap, Tampilan hijau, sidebar berdasarkan peran, halaman admin/petani/petugas.

## Fitur utama

- CRUD Petani, Pupuk, dan Kategori Pupuk.
- Relasi enam tabel: `petani`, `users`, `kategori_pupuk`, `pupuk`, `pemesanan`, dan `pembayaran`.
- Pencarian dan pagination 10 data per halaman pada daftar petani, pupuk, dan pesanan.
- Login berbasis `password_hash()` / `password_verify()` dengan migrasi otomatis untuk password lama berbentuk teks biasa.
- Gambar produk memakai berkas yang tersedia di `public/assets/png/`.

## Akun contoh

Akun contoh pada SQL menggunakan password awal `password`:

- Admin: username `admin`
- Petugas: username `petugas`
- Petani: username/NIK `7201010101000001`

## Struktur File

app/
controllers/Controller.php
models/Repository.php
views/partials/
config/database.php
database/tani_pupuk.sql
public/index.php
public/assets/css/
public/assets/js/
public/assets/png/
