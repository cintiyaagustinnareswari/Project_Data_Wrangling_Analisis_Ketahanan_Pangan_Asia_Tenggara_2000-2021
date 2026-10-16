# Analisis Ketahanan Pangan di Asia Tenggara Menggunakan K-Means Clustering

## 👩‍🎓 Identitas Mahasiswa

- **Nama:** Cintiya Agustin Nareswari
- **NIM:** 24031554218
- **Jenis Tugas:** Ujian Akhir Semester (UAS)
- **Semester:** 3

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis ketahanan pangan di kawasan Asia Tenggara menggunakan pendekatan analisis data dan *machine learning*.

Analisis dilakukan terhadap delapan negara, yaitu Indonesia, Malaysia, Thailand, Vietnam, Filipina, Myanmar, Kamboja, dan Timor Leste, menggunakan data periode 2000–2021.

Analisis berfokus pada tiga aspek utama, yaitu luas lahan pertanian, produksi pangan, dan ketersediaan kalori per kapita. Algoritma **K-Means Clustering** digunakan untuk mengelompokkan negara berdasarkan kemiripan karakteristik dari variabel yang dianalisis.

## 🎯 Tujuan Proyek

1. Mengolah dan menggabungkan data dari beberapa sumber.
2. Menganalisis perkembangan indikator ketahanan pangan di Asia Tenggara.
3. Mengetahui hubungan antarvariabel menggunakan korelasi Spearman.
4. Mengelompokkan negara menggunakan algoritma K-Means Clustering.
5. Mengidentifikasi pola perbedaan karakteristik ketahanan pangan antarnegara.

## 📊 Sumber Data

Proyek ini menggunakan tiga sumber data utama:

1. **World Bank** — data persentase luas lahan pertanian.
2. **World Food Production Dataset** — data produksi komoditas pangan.
3. **Our World in Data** — data ketersediaan kalori per kapita per hari.

Periode analisis mencakup tahun 2000–2021 dengan delapan negara sebagai objek penelitian.

## 🔢 Variabel yang Digunakan

| Variabel | Keterangan |
|---|---|
| Luas Lahan Pertanian | Persentase luas lahan pertanian terhadap total luas daratan |
| Produksi Beras | Produksi beras dalam ton |
| Produksi Jagung | Produksi jagung dalam ton |
| Produksi Minyak Sawit | Produksi minyak sawit dalam ton |
| Produksi Kopi | Produksi kopi dalam ton |
| Produksi Kakao | Produksi kakao dalam ton |
| Produksi Teh | Produksi teh dalam ton |
| Produksi Ubi Jalar | Produksi ubi jalar dalam ton |
| Total Produksi Pangan | Total agregasi komoditas yang dianalisis |
| Kalori per Kapita | Ketersediaan kalori dalam kcal/hari |

## ⚙️ Metode Analisis

Tahapan pengerjaan proyek meliputi:

1. **Data Collection** — mengumpulkan dataset dari berbagai sumber.
2. **Data Cleaning** — membersihkan data, menangani nilai yang hilang, dan menyamakan format data.
3. **Data Integration** — menggabungkan dataset berdasarkan negara dan tahun.
4. **Exploratory Data Analysis (EDA)** — menganalisis data menggunakan statistik deskriptif dan visualisasi.
5. **Data Transformation** — menerapkan transformasi logaritmik `log1p` pada variabel yang sesuai.
6. **Standardization** — menggunakan `StandardScaler` untuk menyamakan skala variabel.
7. **Correlation Analysis** — menganalisis hubungan antarvariabel dengan korelasi Spearman.
8. **Clustering** — menerapkan K-Means dengan penentuan jumlah cluster menggunakan Elbow Method dan Silhouette Score.

## 🧩 Hasil Clustering

Berdasarkan hasil analisis, delapan negara dikelompokkan menjadi tiga cluster:

- **Ketahanan Pangan Tinggi:** Thailand dan Filipina.
- **Ketahanan Pangan Sedang:** Indonesia, Malaysia, dan Myanmar.
- **Ketahanan Pangan Rendah:** Vietnam, Kamboja, dan Timor Leste.

Pengelompokan ini merupakan interpretasi berdasarkan karakteristik variabel yang digunakan. Hasilnya tidak mencakup seluruh dimensi ketahanan pangan, seperti akses ekonomi, kualitas gizi, dan stabilitas pasokan.

## 💡 Kesimpulan

Proyek ini menunjukkan bahwa karakteristik ketahanan pangan di Asia Tenggara berbeda antarnegara. Luas lahan pertanian, produksi pangan, dan ketersediaan kalori per kapita dapat digunakan untuk mengidentifikasi sebagian aspek ketahanan pangan.

Metode K-Means Clustering membantu mengelompokkan negara berdasarkan kemiripan karakteristik data. Melalui proyek ini, analisis data digunakan untuk memperoleh gambaran mengenai pola ketahanan pangan di kawasan Asia Tenggara.

## 🛠️ Tools dan Teknologi

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📚 Referensi Data

- [World Bank Open Data](https://data.worldbank.org/)
- [Our World in Data](https://ourworldindata.org/)
- World Food Production Dataset — Kaggle

---

**Dibuat oleh Cintiya Agustin Nareswari**  
**NIM: 24031554218**  
*Tugas Ujian Akhir Semester — Semester 3*
