# Presentasi Visualisasi Data Film - Kelompok 10

Berikut adalah materi presentasi yang merangkum proyek Tugas Akhir Visualisasi Data. Anda dapat menggunakan *slide* di bawah ini untuk presentasi Anda.

````carousel
# 🎬 Visualisasi Data Film
**Antara Kualitas, Popularitas, & Kesuksesan Finansial**

---
**Tugas Akhir · Mata Kuliah Visualisasi Data**
**Oleh: Kelompok 10**

> Dashboard visualisasi interaktif untuk mengeksplorasi hubungan antara anggaran, skor ulasan, dan pendapatan finansial dalam industri perfilman.

<!-- slide -->
# 📊 Dataset & Metrik Utama

Kami menggunakan data historis dari **Kaggle Movies Dataset** untuk mengungkap tren sinema global.

- **6.820** Judul Film
- **30** Tahun Rentang Waktu (1986 – 2016)
- **15+** Kategori Genre
- **11** Studi Kasus (Visualisasi Interaktif)

> [!NOTE]
> Proyek ini dibangun menggunakan **D3.js** untuk menghadirkan visualisasi yang kaya, dinamis, dan interaktif langsung di peramban web.

<!-- slide -->
# 📈 Tren & Dinamika Genre

Bagaimana selera penonton berubah dari waktu ke waktu?

1. **Tren Genre (Area Chart)**
   Melihat jumlah film per genre yang diproduksi setiap tahunnya dari 1986 hingga 2016.
2. **Era Keemasan Genre (Area Chart)**
   Menemukan tahun-tahun puncak popularitas untuk setiap genre secara spesifik.
3. **Eksplorasi Waktu (Filter Interaktif)**
   Tabel data film yang dapat difilter secara interaktif berdasarkan rentang tahun tertentu untuk analisis spesifik.

<!-- slide -->
# 💰 Korelasi Finansial & Rating

Analisis hubungan sebab-akibat antara modal, kualitas, dan pendapatan.

- **Budget vs Gross (Scatter Plot)**
  *Apakah modal besar selalu mendatangkan untung?* Analisis korelasi antara anggaran produksi dengan pendapatan box office.
- **Score vs Gross (Scatter Plot)**
  *Apakah film bagus selalu laku?* Korelasi antara skor IMDb dengan pendapatan finansial.
- **Skor IMDb per Genre (Bar Chart)**
  Membandingkan rata-rata skor IMDb untuk melihat genre mana yang secara konsisten memiliki kualitas terbaik.

<!-- slide -->
# 💎 Insight Spesifik & Highlight

Temuan-temuan unik dari dataset melalui analisis mendalam.

> [!TIP]
> **Hidden Gems**
> Anomali Scatter Plot: Film-film dengan *budget* sangat rendah namun berhasil mencapai skor rating yang sangat tinggi.

> [!TIP]
> **Popcorn vs Bermutu**
> Bubble Scatter: Membandingkan langsung performa film komersial (blockbuster) melawan sinema berkualitas/seni tinggi.

- **ROI per Genre:** Horizontal Bar Chart yang menampilkan median *Return on Investment* (ROI) tertinggi untuk setiap genre.
- **Reliabilitas Rating:** Menguji keandalan sebuah rating IMDb berdasarkan bobot/jumlah *votes* penonton.

<!-- slide -->
# 🎯 Kesimpulan & Penutup

Dashboard ini memberikan pandangan komprehensif tentang **Lanskap Sinema (1986-2016)**.

**Pertanyaan Kunci yang Terjawab:**
- Kesuksesan finansial tidak melulu bergantung pada *budget* yang raksasa.
- *Genre* tertentu memiliki *Return on Investment* (ROI) yang jauh lebih aman secara statistik.
- Kualitas (Skor IMDb) dan kesuksesan komersial (Gross) memiliki hubungan, namun terdapat banyak anomali (*Hidden Gems*).

---
**Terima Kasih**
*Buka Dashboard interaktif untuk mengeksplorasi visualisasi selengkapnya.*
````
