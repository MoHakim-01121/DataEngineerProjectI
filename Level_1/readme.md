# Level 1: Pemula (Dasar Data Engineering)

Repositori ini berisi proyek Data Engineering tingkat pemula yang membantu memahami dasar-dasar pengolahan data, penyimpanan, dan ekstraksi. 

## Proyek dalam Level 1

### Proyek 1: Membaca dan Menyimpan Data dari CSV ke Database
**Tujuan**: Membaca file CSV, membersihkan data, dan menyimpannya ke database SQLite/PostgreSQL.
**Teknologi**: Python, Pandas, SQLite/PostgreSQL.
**Langkah-langkah**:
1. Membaca file CSV dengan Pandas.
2. Membersihkan data (menghapus nilai kosong, mengubah format harga & tanggal).
3. Menyimpan ke database SQLite/PostgreSQL.

**Dataset yang Digunakan**:
[Titanic Dataset](https://www.kaggle.com/c/titanic/data) - Dataset berisi informasi penumpang kapal Titanic, cocok untuk latihan manipulasi data.

---

### Proyek 2: Web Scraping Data Sederhana
**Tujuan**: Mengambil data dari website (misalnya harga barang dari e-commerce).
**Teknologi**: Python, BeautifulSoup, Requests.
**Langkah-langkah**:
1. Mengambil data produk seperti nama, harga, rating dari website.
2. Menyimpan dalam file CSV.
3. Membuat script yang bisa dijalankan ulang kapan saja.

**Dataset yang Digunakan**:
[Amazon Product Review Data](https://www.kaggle.com/sbhatti/amazon-product-review-dataset) - Dataset berisi data produk, rating, dan ulasan, cocok untuk scraping data dan analisis e-commerce.

---

## Struktur Folder
```
level_1/
│── proyek_1_csv_to_db/
│   ├── data/
│   │   ├── titanic.csv
│   ├── scripts/
│   │   ├── etl.py
│   ├── README.md
│
│── proyek_2_web_scraping/
│   ├── data/
│   │   ├── scraped_products.csv
│   ├── scripts/
│   │   ├── scraper.py
│   ├── README.md
``` 

Setiap proyek memiliki folder tersendiri yang berisi:
- `data/` → Folder tempat menyimpan dataset.
- `scripts/` → Folder yang berisi kode Python untuk menjalankan proyek.
- `README.md` → Dokumentasi proyek.

---

## Cara Memulai

1. Clone repositori:
```bash
git clone https://github.com/username/repository.git
cd repository/level_1
```

2. Install dependensi yang diperlukan:
```bash
pip install -r requirements.txt
```

3. Jalankan proyek sesuai README masing-masing folder

**Note**: Jika mengalami kesulitan atau pertanyaan, silakan buka issue atau pull request.

---

## Next Step
Setelah menyelesaikan level 1, lanjutkan ke [Level 2: Menengah (Automasi dan Pengolahan Data)](../level_2/README.md).
