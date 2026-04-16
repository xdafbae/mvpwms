# MVP WMS (Warehouse Management System)

Proyek ini adalah antarmuka frontend (Minimum Viable Product) untuk **Warehouse Management System (WMS)** yang juga mencakup fitur manajemen inventaris, persetujuan (approval), dan pengajuan multi-kantor.

## 🚀 Fitur Utama

Berdasarkan struktur proyek, berikut adalah modul-modul utama yang tersedia:

1. **Dashboard & Analitik**
   - `dashboard.html`: Halaman utama ringkasan sistem.
   - `stok-dashboard.html`: Dashboard khusus untuk memonitor stok gudang.
   - `target-dashboard.html`: Dashboard untuk memonitor target / pencapaian.

2. **Master Data**
   - `master-barang.html`: Pengelolaan data induk barang/produk.
   - `master-merk.html`: Pengelolaan data induk merk/brand.

3. **Manajemen Pengajuan (Procurement/Request)**
   - `pengajuan-buat.html`: Form pembuatan pengajuan baru oleh staf/kantor.
   - `pengajuan-riwayat.html`: Melihat riwayat atau status pengajuan yang telah dibuat.
   - `approval-inbox.html`: Kotak masuk persetujuan (approval) untuk atasan/manajemen.

4. **Manajemen Gudang**
   - `gudang-inbox.html`: Kotak masuk tugas/task gudang, seperti barang masuk atau siap packing.
   - `office-select.html`: Fitur untuk memilih atau beralih cabang kantor/gudang (multi-office).

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3
- JavaScript (Vanilla)

## 📌 Cara Menggunakan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/xdafbae/mvpwms.git
   ```
2. Buka salah satu file HTML, misalnya `index.html`, langsung menggunakan browser atau dengan menjalankan *Live Server* di editor kode (seperti VSCode) untuk pengalaman pengembangan yang lebih baik.

---
*README ini akan terus diperbarui seiring dengan perkembangan fitur pada aplikasi.*
