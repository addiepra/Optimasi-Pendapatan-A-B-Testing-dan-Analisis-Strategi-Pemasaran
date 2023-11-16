# Optimasi Pendapatan: A/B Testing dan Analisis Strategi Pemasaran


## Pendahuluan
Dalam lingkungan kerja yang dinamis di sebuah toko online besar, saya, sebagai seorang data analyst, bersama dengan tim pemasaran, telah berkolaborasi untuk mengidentifikasi potensi peningkatan pendapatan. Sebagai hasilnya, kami telah merumuskan serangkaian hipotesis yang dapat menjadi kunci untuk meningkatkan kinerja toko secara keseluruhan. Tugas utama saya dalam Project adalah melakukan pemilahan dan prioritisasi terhadap hipotesis-hipotesis tersebut. Proses ini melibatkan implementasi A/B testing yang akan membantu kami mengumpulkan data yang relevan dan signifikan. Selanjutnya, saya akan melakukan analisis mendalam terhadap hasil-hasil tersebut untuk menghasilkan wawasan yang dapat diimplementasikan guna mengoptimalkan strategi pemasaran dan meningkatkan pendapatan toko online ini. Dengan fokus pada metodologi sprint dan kolaborasi tim, Project diharapkan dapat memberikan kontribusi positif terhadap pertumbuhan dan kesuksesan toko online ini.

## Tujuan
Tujuan Project secara singkat adalah meningkatkan pendapatan toko online dengan melakukan pemilahan, prioritisasi, dan pengujian hipotesis melalui A/B testing. Melalui analisis hasil, kami berharap dapat mengidentifikasi strategi pemasaran yang efektif dan optimal untuk meningkatkan kinerja toko secara keseluruhan.

## Tahapan
Berikut tahapan-tahapan yang akan kita lakukan:

1. Memprioritaskan Hipotesis
File `hypotheses_us.csv` memuat sembilan hipotesis untuk meningkatkan pendapatan toko online dengan Reach, Impact, Confidence, dan Effort yang sudah ditentukan untuk masing-masing hipotesis.
dengan tugas yang dilakukan adalah:
- Menerapkan framework ICE untuk memprioritaskan hipotesis. Urutkan hipotesis tersebut dalam urutan prioritas menurun.
- Menerapkan framework RICE untuk memprioritaskan hipotesis. Urutkan hipotesis tersebut dalam urutan prioritas menurun.
- Menunjukkan perubahan prioritas hipotesis saat RICE diterapkan untuk menggantikan ICE. Berikan penjelasan terkait perubahan tersebut.

2. Analisis A/B Testing
Melakukan A/B testing dan mendapatkan hasil seperti yang dideskripsikan dalam file `orders_us.csv` dan `visitors_us.csv`. Berikut sub bab yang akan dilakukan:

- Gambarkan pendapatan kumulatif berdasarkan kelompok. Buat kesimpulan dan asumsinya.
- Gambarkan ukuran pesanan rata-rata kumulatif berdasarkan kelompok. Buat kesimpulan dan asumsinya.
- Gambarkan perbedaan relatif untuk ukuran pesanan rata-rata kumulatif kelompok B yang dibandingkan dengan kelompok A. Buat kesimpulan dan asumsinya.
- Gambarkan konversi kumulatif berdasarkan kelompok. Buat kesimpulan dan asumsinya.
- Gambarkan perbedaan relatif untuk tingkat konversi kumulatif kelompok B yang dibandingkan dengan kelompok A. Buat kesimpulan dan asumsinya.
- Hitung tingkat konversi setiap kelompok sebagai rasio pesanan terhadap jumlah kunjungan setiap hari. Buat grafik tingkat konversi harian dari kedua kelompok dan jelaskan perbedaannya. Buat kesimpulan dan asumsinya.
- Buat diagram tebar (scatter chart) untuk jumlah pesanan per pengguna. Buat kesimpulan dan asumsinya.
- Hitung persentil ke-95 dan ke-99 untuk jumlah pesanan per pengguna. Tentukan titik ketika suatu titik data berubah menjadi anomali.
- Buat diagram tebar (scatter chart) untuk harga pesanan. Buat kesimpulan dan asumsinya.
- Hitung persentil ke-95 dan ke-99 untuk harga pesanan. Tentukan titik ketika suatu titik data berubah menjadi anomali.
- Temukan signifikansi statistik perbedaan konversi antar kelompok menggunakan data mentah. Buat kesimpulan dan asumsinya.
- Temukan signifikansi statistik perbedaan ukuran pesanan rata-rata antar kelompok menggunakan data mentah. Buat kesimpulan dan asumsinya.
- Temukan signifikansi statistik perbedaan konversi antar kelompok menggunakan data yang telah difilter. Buat kesimpulan dan asumsinya.
- Temukan signifikansi statistik perbedaan ukuran pesanan rata-rata antar kelompok menggunakan data yang telah difilter. Buat kesimpulan dan asumsinya.
- Buatlah keputusan berdasarkan hasil pengujian. Keputusan yang memungkinkan adalah: 1. Menghentikan pengujian, serta mempertimbangkan salah satu kelompok sebagai pemimpin. 2. Menghentikan pengujian, serta menyimpulkan bahwa tidak ada perbedaan antara kedua kelompok. 3. Melanjutkan pengujian.
 
