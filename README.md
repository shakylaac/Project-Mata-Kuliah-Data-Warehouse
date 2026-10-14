# Implementasi Data Warehouse dan OLAP untuk Analisis Pemesanan Hotel dan Perilaku Pelanggan

## Deskripsi Proyek
Proyek ini bertujuan untuk menerapkan konsep Data Warehouse dan Online Analytical Processing (OLAP) dalam menganalisis data pemesanan hotel dan perilaku pelanggan. Analisis dilakukan untuk memperoleh informasi mengenai jumlah pemesanan, pembatalan reservasi, pendapatan hotel, serta karakteristik pelanggan.
Proyek ini menggunakan pendekatan analisis multidimensional melalui Atoti untuk mengolah data dan menyajikan informasi dalam bentuk dashboard. Hasil analisis diharapkan dapat membantu memahami pola pemesanan dan mendukung pengambilan keputusan berdasarkan data.

## Dataset
- **Nama Dataset:** Hotel Booking Demand
- **Sumber:** [Kaggle – Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- **Deskripsi:** Dataset berisi informasi pemesanan pada City Hotel dan Resort Hotel, termasuk waktu pemesanan, durasi menginap, jumlah tamu, jenis pelanggan, saluran pemesanan, dan status pembatalan.
- **Tujuan Penggunaan:** Dataset digunakan untuk membangun analisis multidimensional dan mengevaluasi pola pemesanan serta perilaku pelanggan hotel.

## Teknologi yang Digunakan
- Python
- Jupyter Notebook
- Pandas
- Atoti

## Metode yang Digunakan
### 1. Data Warehouse
Konsep Data Warehouse digunakan untuk menyiapkan dan mengorganisasi data pemesanan hotel agar dapat dianalisis secara terstruktur.
### 2. Online Analytical Processing (OLAP)
OLAP digunakan untuk menganalisis data dari berbagai dimensi, seperti jenis hotel, waktu pemesanan, dan karakteristik pelanggan, sehingga pola dan informasi penting dapat diketahui.
### 3. Dashboard dan Visualisasi Data
Atoti digunakan untuk menyajikan hasil pengolahan data dalam bentuk dashboard yang memudahkan pemantauan indikator dan eksplorasi informasi pemesanan hotel.

## Tahapan Pengerjaan
1. **Data Understanding** — memahami struktur dan karakteristik dataset.
2. **Data Preprocessing** — mempersiapkan dan mengolah data sebelum dianalisis.
3. **Data Modeling** — menyusun data untuk mendukung analisis multidimensional.
4. **Implementasi OLAP** — mengolah data menggunakan Atoti agar dapat dianalisis berdasarkan berbagai dimensi.
5. **Pembuatan Dashboard** — menyajikan hasil analisis dalam bentuk visualisasi dan indikator.
6. **Analisis Hasil** — menginterpretasikan informasi mengenai pemesanan, pembatalan, pendapatan, dan perilaku pelanggan.

## Key Performance Indicators (KPI)
Dashboard menggunakan beberapa indikator utama, yaitu:
- **Total Bookings** — jumlah pemesanan hotel.
- **Canceled Bookings** — jumlah pemesanan yang dibatalkan.
- **Cancellation Rate** — persentase pemesanan yang dibatalkan.
- **ADR (Average Daily Rate)** — rata-rata tarif harian kamar.
- **Estimated Revenue** — estimasi pendapatan berdasarkan perhitungan yang digunakan dalam proyek.

## Hasil dan Tujuan
Proyek ini menghasilkan analisis data pemesanan hotel melalui pendekatan Data Warehouse dan OLAP serta visualisasi dashboard menggunakan Atoti. Analisis mencakup perbandingan City Hotel dan Resort Hotel, tingkat pembatalan reservasi, estimasi pendapatan, dan karakteristik pelanggan.
Melalui proyek ini, konsep pengolahan data multidimensional, penerapan OLAP, dan visualisasi data dapat dipahami secara langsung untuk mendukung analisis bisnis berbasis data.
