# 🛠️ Portofolio Web Inventaris Tools Management

Aplikasi **Web Portofolio Manajemen Inventaris Tools** berbasis *Single Page Application (SPA)* yang dirancang untuk mengelola stok, status transaksi keluar/masuk, serta kondisi fisik peralatan kerja (*tools*).

Aplikasi ini dibangun menggunakan **HTML5**, **Tailwind CSS**, dan **Vanilla JavaScript** tanpa dependensi backend eksternal, dengan sistem penyimpanan data lokal (*LocalStorage*).

---

## 🌟 Fitur Utama

- **🔐 Autentikasi Login (Simulasi & Pengaman Akses)**:
  - Proteksi halaman dasbor dengan validasi kredensial login.
  - Memblokir akses dan menampilkan notifikasi peringatan jika username atau password salah.
- **📊 Dashboard Ringkasan Indikator**:
  - Menampilkan kartu statistik *real-time*: **Total Jenis Tools**, **Total Kuantitas (QTY)**, serta jumlah unit berdasarkan kondisi fisik (**B = Baik**, **RR = Rusak Ringan**, **RB = Rusak Berat**).
- **📦 Kelola Inventaris Tools (CRUD)**:
  - Pencatatan atribut barang lengkap: **Nama Barang**, **Part Number (P/N)**, **Serial Number (S/N)**, **QTY**, **Status Transaksi (Masuk/Keluar)**, **Kondisi (B/RR/RB)**, dan **Keterangan**.
  - Operasi Tambah, Edit, dan Hapus data secara interaktif.
- **🔍 Pencarian & Filter Dinamis**:
  - Pencarian cepat (*real-time search*) berdasarkan kata kunci Nama Barang, P/N, S/N, atau Keterangan.
  - Filter kustom berdasarkan status kondisi barang (`B`, `RR`, atau `RB`).
- **📊 Ekspor Data ke CSV / Excel**:
  - Fitur ekspor seluruh data inventaris ke berkas `.csv` yang langsung kompatibel dengan Microsoft Excel (dilengkapi BOM UTF-8).
- **🖨️ Cetak PDF / Print Laporan Fisik**:
  - Fitur cetak laporan resmi dengan tampilan khusus cetak (*Print View* `@media print`) yang bersih dari tombol navigasi dan dilengkapi **Kop Surat Laporan Resmi**.
- **💾 Persistent State**:
  - Seluruh perubahan data tersimpan di *LocalStorage* browser sehingga data tidak hilang saat halaman di-*refresh*.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Struktur semantic halaman web.
- **Tailwind CSS (CDN)**: Styling antarmuka yang modern, responsif, dan rapi.
- **FontAwesome**: Ikonografi interaktif.
- **Vanilla JavaScript (ES6+)**: Logika aplikasi, manipulasi DOM, manajemen state LocalStorage, serta modul ekspor & cetak.

---

## 🚀 Cara Menjalankan Aplikasi Secara Lokal

1. **Clone Repositori**:
   ```bash
   git clone [suspicious link removed]
