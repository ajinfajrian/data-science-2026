# Portofolio Data Science - Aktivitas Praktikum Sesi 1 s/d 7
---

## Identitas Mahasiswa
* **Nama Lengkap** : Fajrian Ichlasul Maruto
* **NIM** : 240401020100
* **Kelas** : IF401
* **Program Studi** : S1 PJJ Informatika
* **Institusi** : Universitas Siber Asia

---

## Deskripsi Repositori
Repositori ini dibangun dan didekasikan khusus sebagai pemenuhan berkas portofolio **Ujian Tengah Semester (UTS)** pada mata kuliah **Data Science (Genap 2025/2026)**. 

Portofolio ini merangkum seluruh aktivitas eksperimen interaktif berbasis Jupyter Notebook (`.ipynb`) dari Pertemuan 1 hingga Pertemuan 7. Alur pengerjaan di dalam repositori ini mengadopsi standar industri **CRISP-DM (Cross-Industry Standard Process for Data Mining)**, yang melatih pemrosesan data mentah yang tidak terstruktur (*dirty data*), eksplorasi statistik deskriptif (*Exploratory Data Analysis*), rekayasa fitur data (*data preprocessing*), hingga visualisasi prediktif menggunakan algoritma *Machine Learning Supervised Learning*.

---

## Daftar Isi

Seluruh lembar kerja berikut telah dieksekusi penuh secara bertahap dan mempertahankan rekaman output program (teks, tabel, dan grafik visual) tanpa memerlukan eksekusi ulang (*ready-to-view*):

| Sesi | Pembahasan Modul / Aktivitas Praktikum | Jenis Dataset yang Digunakan | Tautan File Kerja Interaktif |
| :---: | :--- | :---: | :---: |
| **01** | **Pengenalan & Sintaks Dasar Python**<br>• Konstruksi `print()`, variabel, enumerasi `list`, loop, dan f-string. | Python Native String | [Lihat Notebook Sesi 1](./Pertemuan1_Fajrian_Ichlasul_240401020100.ipynb) |
| **02** | **Struktur Data Dasar & Library Pandas**<br>• Inspeksi awal dimensi DataFrame, `.info()`, dan filter data berkelompok. | Titanic Open Dataset | [Lihat Notebook Sesi 2](./Pertemuan2_Fajrian_Ichlasul_240401020100.ipynb) |
| **03** | **Data Cleaning Pipeline**<br>• Handling missing values, standardisasi teks kategori, dan Clipping Outliers via IQR. | Housing Dirty CSV | [Lihat Notebook Sesi 3](./Pertemuan3_Fajrian_Ichlasul_240401020100.ipynb) |
| **04** | **Statistika Deskriptif & Analisis EDA**<br>• Perhitungan Mean, Median, Variance, Skewness, Kurtosis, dan Heatmap matriks. | Iris Dataset (Seaborn) | [Lihat Notebook Sesi 4](./Pertemuan4_Fajrian_Ichlasul_240401020100.ipynb) |
| **05** | **Visualisasi Data & Narasi Storytelling**<br>• Implementasi framework narasi visual kualitatif *What? So What? Now What?* | Titanic Open Dataset | [Lihat Notebook Sesi 5](./Pertemuan5_Fajrian_Ichlasul_240401020100.ipynb) |
| **06** | **Data Preparation & Preprocessing Pipeline**<br>• One-Hot Encoding, StandardScaler, dan Stratified Train-Test Split. | Titanic Open Dataset | [Lihat Notebook Sesi 6](./Pertemuan6_Fajrian_Ichlasul_240401020100.ipynb) |
| **07** | **Pengantar Machine Learning: Regresi Linear**<br>• Prediksi nilai kontinu (`fare`), evaluasi metrik MAE, RMSE, $R^2$, dan Residual plot. | Titanic Open Dataset | [Lihat Notebook Sesi 7](./Pertemuan7_Fajrian_Ichlasul_240401020100.ipynb) |

---

## Spesifikasi Tools & Modules

Eksperimen portofolio ini dikembangkan menggunakan ekosistem cloud-computing **Google Colaboratory** dengan spesifikasi infrastruktur perangkat lunak sebagai berikut:

### 1. Perangkat Lunak Utama & Environment
* **Runtime Jaringan**: Google Colab Virtual Machine (Ubuntu Linux Backend)
* **Bahasa Pemrograman**: Python 3.10+
* **Sistem Kontrol Versi**: Git & GitHub Engine

### 2. Pustaka Pemrosesan & Manipulasi Data (Data Wrangling)
* **`NumPy` (v1.25+)**: Digunakan untuk operasi komputasi berbasis vektor, manipulasi array multi-dimensi, pembentukan struktur matriks, serta penanganan konversi objek kosong (`np.nan`).
* **`Pandas` (v2.0+)**: Berperan sebagai core engine pembuatan struktur data tabular (DataFrame & Series), pembacaan file eksternal (CSV/JSON), pembersihan data duplikat, pengisian nilai kosong (`.fillna()`), korelasi matriks, dan agregasi data `.groupby()`.

### 3. Pustaka Analisis Statistik & Matematika
* **`SciPy` (Sub-modul `scipy.stats`)**: Digunakan secara khusus pada pengerjaan analisis statistika tingkat lanjut untuk mengukur derajat kecondongan kurva distribusi data (*Skewness*) dan keruncingan grafik (*Kurtosis*).

### 4. Pustaka Visualisasi Data (Data Visualization)
* **`Matplotlib` (v3.7+)**: Digunakan sebagai fondasi dasar pembuatan struktur objek grafik (*figure* dan *axes*), bar chart dasar, pengaturan label sumbu kartesius, penentuan batas limitasi angka, serta layouting panel gambar ganda berdampingan (`plt.subplots`).
* **`Seaborn` (v0.12+)**: Berperan dalam pembuatan plot statistik tingkat lanjut yang interaktif dan modern, meliputi kurva KDE (Kernel Density Estimate), Scatter plot korelasi sebaran titik, countplot kategori biner, Boxplot deteksi kuartil pencilan, serta Heatmap korelasi gradasi warna.

### 5. Perangkat Algoritma Machine Learning
* **`Scikit-Learn` (`sklearn`)**: Berperan penuh dalam fase pemodelan cerdas, menggunakan sub-modul:
  * `sklearn.model_selection.train_test_split` untuk pembagian subset data latih & data uji.
  * `sklearn.preprocessing.StandardScaler` untuk Z-score feature scaling.
  * `sklearn.preprocessing.OneHotEncoder` untuk Categorical string binarization.
  * `sklearn.linear_model.LinearRegression` sebagai core model algoritma regresi prediktif.
  * `sklearn.metrics` (`mean_absolute_error`, `mean_squared_error`, `r2_score`) untuk validasi akurasi performa model.

---

## Kesimpulan
Rangkaian praktikum dari Sesi 1 hingga Sesi 7 ini memberikan pemahaman yang sangat berharga bagi saya mengenai dasar-dasar kerja seorang *Data Scientist* profesional. 

Melalui pembelajaran ini, saya menyadari bahwa visualisasi canggih atau algoritma Machine Learning yang rumit tidak akan memberikan hasil yang akurat tanpa didahului oleh proses pembersihan data (*Data Cleaning*) dan persiapan data (*Data Preprocessing*) yang matang. Penerapan metode pemotongan pencilan menggunakan rumus IQR Fence, penguncian distribusi target lewat *stratified split*, standardisasi skala fitur, serta analisis visual berbasis data interpretasi kualitatif (*What? So What? Now What?*) mengajarkan saya untuk tidak hanya menjadi seorang programmer yang menulis baris kode, tetapi juga menjadi seorang analis yang mampu mengekstrak nilai bermakna dari balik tumpukan data mentah. Portofolio ini menjadi pondasi dasar yang kuat bagi saya untuk melangkah ke metodologi kecerdasan buatan (*Artificial Intelligence*) yang lebih kompleks di masa mendatang.
