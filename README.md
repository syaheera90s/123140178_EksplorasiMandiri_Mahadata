# Eksplorasi Mandiri Mahadata: Apache Spark untuk Prediksi Smart Grid

Repositori ini berisi kode eksperimen replikasi parsial dari artikel jurnal:
> Ali, H. A. E.-S., Alham, M. H., & Ibrahim, D. K. (2024). *Big data resolving using Apache Spark for load forecasting and demand response in smart grid: A case study of Low Carbon London Project*. Journal of Big Data. DOI: 10.1186/s40537-024-00909-6.

## Spesifikasi Sistem & Pustaka (Requirements)
* Platform: Google Colab
* Versi Python: 3.13.15
* Pustaka yang digunakan tercantum dalam file `requirements.txt` (termasuk `pyspark==4.0.4` dan `kagglehub`).

## Persiapan dan Cara Menjalankan Kode (Langkah Reproduksi)
1. **Buka Kode:** Buka file `123140178_EksplorasiMandiri_Mahadata.ipynb` di Google Colab.
2. **Instalasi:** Pastikan untuk menjalankan sel kode (cell) pertama terlebih dahulu agar lingkungan Colab otomatis mengunduh dan memasang pyspark serta kagglehub sesuai daftar di requirements.txt.
3. **Pengunduhan Data:** Skrip pengunduhan data telah disertakan di dalam *notebook*. Jalankan sel kode yang memuat modul `kagglehub` untuk mengunduh dataset secara otomatis dari Kaggle (`jeanmidev/smart-meters-in-london`), tidak perlu mengunduh data secara manual.
4. **Reproduksi Hasil:** Jalankan sisa sel kode secara berurutan (Run All). Hasil utama berupa nilai evaluasi model (*Root Mean Squared Error* / RMSE) akan tercetak secara otomatis di bagian akhir *notebook*.
