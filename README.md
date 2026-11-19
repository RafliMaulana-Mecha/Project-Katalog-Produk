# Aplikasi Katalog Produk (JavaFX)

Proyek ini merupakan implementasi tugas mata kuliah **Pemrograman Lanjut** berupa aplikasi desktop berbasis **JavaFX** dan database **SQLite** untuk mengelola data katalog produk dengan operasi **CRUD** (*Create, Read, Update, Delete*) secara lengkap.

---

* **Nama:** Rafli Maulana
* **NIM:** 2404364
* **Kelas:** 3B

---

## Fitur Utama
* **Tambah Produk (Create):** Menambahkan data produk baru (nama, harga, dan foto produk) lengkap dengan validasi input.
* **Tampilan Katalog Interaktif (Read):** Menampilkan daftar produk dalam bentuk kartu katalog interaktif beserta penghitung jumlah total produk.
* **Edit Produk (Update):** Memperbarui informasi data produk yang sudah tersimpan di dalam database.
* **Hapus Produk (Delete):** Menghapus data produk yang dipilih dengan dialog konfirmasi keamanan untuk mencegah penghapusan tidak disengaja.
* **Penyimpanan Persisten:** Menggunakan database lokal SQLite (`data/katalog.db`) sehingga data tetap tersimpan meskipun aplikasi ditutup.

---

## Persyaratan Sistem
Sebelum menjalankan proyek, pastikan lingkungan pengembangan Anda telah terpasang komponen berikut:
* **Java Development Kit (JDK)** versi 11 atau lebih baru.
* **Apache NetBeans IDE** (dengan dukungan Apache Maven).
* **JavaFX SDK / Library** & **SQLite JDBC Driver** (terkonfigurasi melalui Maven/Libraries proyek).

---

## Cara Menjalankan Proyek
1. **Clone** atau unduh repositori ini ke komputer lokal Anda.
2. Buka **Apache NetBeans IDE**, lalu pilih **File > Open Project** dan arahkan ke folder proyek `KatalogProduk`.
3. Pada panel *Projects*, buka direktori *Source Packages* > *package* `main`, lalu cari file `MainApp.java`.
4. Klik kanan pada file `MainApp.java` dan pilih **Run File** (atau tekan `Shift + F6`), atau jalankan keseluruhan proyek melalui **Run Project** (`F6`).

---

## Screenshot Aplikasi
<img width="1252" height="988" alt="image" src="https://github.com/user-attachments/assets/2c8fab2a-5e05-4afc-9583-5b0349238bbe" />
<img width="1248" height="981" alt="image" src="https://github.com/user-attachments/assets/5eebe4c8-251c-41f8-b5e8-30b32d20c8e7" />

