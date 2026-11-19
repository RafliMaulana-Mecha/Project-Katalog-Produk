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
### 1. Tampilan Awal
<img width="1252" height="988" alt="image" src="https://github.com/user-attachments/assets/188e265e-6ef0-4478-9274-0d094511fbd6" />

### 2. Tampilan Edit Produk
<img width="1252" height="988" alt="image" src="https://github.com/user-attachments/assets/0fffccb7-eb0c-4349-9cb6-843cc6b98de6" />

### 3. Tampilan Setelah Produk diedit
<img width="1252" height="988" alt="image" src="https://github.com/user-attachments/assets/3e49d5d7-345b-4dcb-ae92-7ae22dfcf41c" />

### 4. Tampilan untuk Hapus Produk
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/c3ffb47a-f16f-4072-8ca3-3d1aa3e21a9a" />

### 5. Tampilan Setelah Produk berhasil dihapus
<img width="1252" height="988" alt="image" src="https://github.com/user-attachments/assets/9d3199d8-b376-41c0-8283-7607d960f6fd" />
