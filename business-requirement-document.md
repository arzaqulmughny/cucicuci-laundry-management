# Business Requirement Document (BRD): Laundry Management System

## 1. Executive Summary
Aplikasi sistem informasi laundry ini dirancang untuk menggantikan pencatatan manual yang dilakukan oleh staf laundry dengan sistem digital berbasis web atau mobile. Sistem ini bertujuan meningkatkan efisiensi operasional, meminimalkan kesalahan pencatatan, dan memberikan pengalaman pelanggan yang lebih baik.

## 2. Objectives
- Meningkatkan efisiensi dalam pencatatan pesanan laundry.
- Memberikan transparansi proses kepada pelanggan.
- Mengurangi risiko kehilangan data akibat pencatatan manual.
- Menyediakan laporan operasional yang dapat diakses kapan saja.

## 3. Scope
### In-Scope:
- Pencatatan jumlah pakaian, berat (dalam kilogram), jenis bahan, dan layanan tambahan.
- Fitur pengelolaan pesanan (pembuatan, pembaruan, pembatalan).
- Notifikasi status pesanan kepada pelanggan.
- Dashboard untuk staf laundry.
- Fitur laporan keuangan dan operasional.

### Out-of-Scope:
- Integrasi dengan alat cuci otomatis.
- Pembayaran melalui cryptocurrency.

## 4. Stakeholders
- **Owner/Manager Laundry:** Mengawasi operasional dan mengakses laporan.
- **Staf Laundry:** Mencatat pesanan dan memproses laundry.
- **Pelanggan:** Memesan layanan dan melacak status pesanan.

## 5. Functional Requirements
1. **Manajemen Pesanan:**
   - Staf dapat mencatat pesanan baru dengan rincian:
     - Nama pelanggan.
     - Berat pakaian.
     - Jenis bahan.
     - Layanan tambahan (misalnya, pewangi khusus).
   - Pelanggan dapat melacak status pesanan (dalam proses, selesai, diambil).
2. **Notifikasi:**
   - Mengirimkan notifikasi ke pelanggan saat:
     - Pesanan diproses.
     - Pesanan selesai.
3. **Dashboard Admin:**
   - Laporan harian, mingguan, dan bulanan terkait jumlah pesanan, pendapatan, dan jumlah pakaian yang dicuci.
   - Filter data berdasarkan periode tertentu.
4. **Manajemen Staf:**
   - Admin dapat menambah atau menghapus akun staf.
5. **Laporan Keuangan:**
   - Rekap data pendapatan dari pesanan.

## 6. Non-Functional Requirements
- **Kecepatan:** Sistem harus dapat memproses pesanan dalam waktu kurang dari 5 detik.
- **Keamanan:**
  - Data pelanggan harus dienkripsi.
  - Sistem hanya dapat diakses oleh pengguna yang memiliki hak akses.
- **Skalabilitas:** Sistem harus dapat menangani hingga 500 pesanan per hari tanpa penurunan performa.
- **Responsiveness:**
  - Tampilan aplikasi harus responsif dan dapat diakses di perangkat desktop dan mobile.

## 7. Risks and Mitigations
| Risiko                          | Mitigasi                                |
|--------------------------------|----------------------------------------|
| Kehilangan data akibat crash   | Implementasi sistem backup otomatis.   |
| Kesalahan input oleh staf      | Validasi data sebelum disimpan.        |
| Keterbatasan staf memahami sistem | Pelatihan awal untuk staf sebelum implementasi. |

## 8. Timeline
| Tahapan                 | Perkiraan Waktu |
|-------------------------|-----------------|
| Analisis kebutuhan      | 1 minggu        |
| Desain UI/UX            | 2 minggu        |
| Pengembangan sistem     | 4 minggu        |
| Pengujian               | 2 minggu        |
| Implementasi dan pelatihan | 1 minggu     |

## 9. Budget Estimation
- Perkiraan anggaran:
  - Pengembangan aplikasi: Rp 20.000.000.
  - Pelatihan staf: Rp 2.000.000.
  - Infrastruktur server: Rp 3.000.000 per tahun.

## 10. Approval
Tanda tangan di bawah ini menunjukkan bahwa dokumen ini telah disetujui:

| Nama                 | Posisi               | Tanggal       |
|----------------------|----------------------|---------------|
| Arzaqul Mughny      | Sistem Analis       | [Tanggal]     |
| [Nama Manager]       | Manager Laundry     | [Tanggal]     |

