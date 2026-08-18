# Analisa Penjualan Warung Sembako
<img width="1515" height="902" alt="Screenshot 2026-08-19 011430" src="https://github.com/user-attachments/assets/69b7de10-862d-448f-b61c-c110a359d36e" />

## Deskripsi
Proyek ini berisi visualisasi data interaktif untuk menganalisis performa transaksi harian pada warung sembako. Dashboard ini dibangun menggunakan Tableau untuk memberikan *insight* teknis terkait penjualan produk, kinerja kasir, metode pembayaran, dan tren pendapatan.

## Tools & Teknologi
*   **Data Cleaning:** Python (Pandas)
*   **Visualisasi:** Tableau Desktop
*   **Dataset:** `data_transaksi_warung_sembako.csv`

## 📈 Insight Analitik Utama
*   **Dominasi Volume FMCG:** Indomie Kuah Ayam Spesial (2.665 unit) dan seri Bumbu Racik memimpin metrik volume. 
    *   *Rekomendasi:* Optimalkan *buffer stock* dan *reorder point* pada sistem inventaris.
*   **Anomali Tren Penjualan 2026:** Terjadi penurunan tajam *revenue* di tahun 2026 (Rp 1,77 Miliar) dibandingkan 2025 (Rp 3,48 Miliar). 
    *   *Catatan Data:* Data 2026 berstatus *Year-to-Date* (YTD), belum mencerminkan satu tahun penuh.
*   **Adopsi Pembayaran Digital Tinggi:** QRIS mendominasi 60% total frekuensi transaksi (24 dari 40 sampel struk). 
    *   *Rekomendasi:* Infrastruktur pembayaran *cashless* dipertahankan; fokuskan rekonsiliasi kas pada *settlement* QRIS.
*   **Distribusi Beban Shift Merata:** Nilai transaksi kelima kasir berada pada *range* ketat (Rp 1,67 Miliar - Rp 1,78 Miliar), dipimpin oleh Siti. 
    *   *Kesimpulan:* Beban kerja *shift* antar kasir terdistribusi secara efisien.

## Cara Menjalankan (Deployment)
1. Buka terminal atau *command prompt*.
2. Lakukan *clone* repositori ini:
   ```bash
   git clone [https://github.com/Yogaarsyad/Analisa-Penjualan-Warung-Sembako.git](https://github.com/Yogaarsyad/Analisa-Penjualan-Warung-Sembako.git)
