<<<<<<< HEAD
# DataEngineerProjectI
Kumpulan proyek data engineering open source
=======
# Proyek 1: Data Cleaning & Transformasi Dasar  

## 📌 Deskripsi  
Proyek ini bertujuan untuk membersihkan dan mentransformasi dataset **NYC Taxi Fare Prediction** agar siap digunakan untuk analisis lebih lanjut. Langkah-langkah utama dalam proyek ini mencakup pembacaan data, pembersihan, dan transformasi data ke format yang lebih efisien seperti **Parquet** atau **Avro**.  

## 🎯 Tujuan  
- Memahami dasar-dasar **data cleaning** dalam data engineering.  
- Menggunakan **Pandas** dan **DuckDB** untuk mengelola data.  
- Mengonversi dataset ke format yang lebih optimal untuk analisis.  

## 📊 Dataset  
Dataset yang digunakan adalah **NYC Taxi Fare Prediction**, yang berisi informasi tentang perjalanan taksi di New York City, termasuk:  
- **pickup_datetime** → Waktu penjemputan taksi.  
- **pickup_longitude & pickup_latitude** → Koordinat lokasi awal.  
- **dropoff_longitude & dropoff_latitude** → Koordinat tujuan.  
- **fare_amount** → Total biaya perjalanan.  

Dataset ini dapat diunduh dari [Kaggle](https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/data).  

## 🛠️ Tools yang Digunakan  
- **Python** → Bahasa pemrograman utama.  
- **Pandas** → Digunakan untuk manipulasi dan analisis data.  
- **DuckDB** → Database SQL ringan untuk query tanpa server.  
- **Docker** → Untuk menjalankan aplikasi dalam container.  

## 🔨 Langkah-langkah  
1. **Baca Dataset** menggunakan **Pandas**.  
2. **Bersihkan Data**:  
   - Hapus duplikat.  
   - Tangani nilai yang hilang (missing values).  
   - Konversi kolom **pickup_datetime** ke format yang benar.  
3. **Transformasi Data**:  
   - Simpan dataset dalam format **Parquet** untuk efisiensi penyimpanan.  
4. **Gunakan DuckDB** untuk menjalankan query terhadap dataset tanpa database server besar.  

## 🚀 Instalasi  
1. Clone repositori ini:  
   ```bash
   git clone https://github.com/username/data-engineering-projects.git
2. Masuk ke direktori proyek:
  ```bash
  cd cd data-engineering-projects/1-data-cleaning-transformation
3. Instalasi dependencies:
  ```bash
  pip install -r requirements.txt
>>>>>>> 95305c9 (Menambahkan proyek 1: Data Cleaning & Transformasi)
