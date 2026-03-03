<div align="center">
  <img src="https://github.com/nflora-ux/Operating-System-MySQL-v2/raw/main/Screenshot.png" alt="Screenshot OSM v2" width="600">
</div>

# MySQL Operations Tool v2

Tools interaktif berbasis Node.js untuk mengelola database MySQL melalui terminal.  
Versi 2 menghadirkan antarmuka yang lebih modern dan interaktif dengan dukungan **Inquirer.js**.

## Fitur Unggulan
- Manajemen database (lihat, buat, hapus, pilih database)
- Manajemen tabel (lihat, buat, hapus, lihat struktur, lihat isi tabel)
- Operasi CRUD data:
  - **INSERT** – tambah data dengan panduan kolom
  - **SELECT** – cari data dengan filter interaktif (WHERE)
  - **UPDATE** – ubah data dengan pemilihan kolom dan kondisi
  - **DELETE** – hapus data dengan kondisi atau tanpa kondisi (dengan konfirmasi)
- Eksekusi query SQL bebas (menggunakan editor)
- Tampilan warna-warni untuk pesan sukses, error, dan peringatan
- Koneksi fleksibel: host, port, user, password, database awal
- Pool koneksi untuk performa optimal

## Cara Penggunaan
1. Clone repositori ini:
   ```bash
   git clone https://github.com/nflora-ux/Operating-System-MySQL-v2.git
   ```
2. Masuk ke direktori proyek dan instal dependensi:
   ```bash
   cd Operating-System-MySQL-v2
   ```
   ```bash
   npm install
   ```
4. Jalankan aplikasi:
