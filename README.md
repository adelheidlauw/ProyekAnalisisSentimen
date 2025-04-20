# Proyek Analisis Sentimen
# UlasanAplikasi Grab ID

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap ulasan pengguna aplikasi Grab ID. Proses dilakukan dari scraping data, preprocessing, pelatihan model, hingga evaluasi model analisis sentimen.

## Struktur Proyek
```
├── Kode_Scraping_Proyek_Analisis_Sentimen_Adelheid_Chantal_Lauw.ipynb        # Notebook untuk web scraping data.
├── Notebook_Pelatihan_Proyek_Analisis_Sentimen_Adelheid_Chantal_Lauw.ipynb   # Notebook untuk pelatihan model machine learning
├── requirements.txt                                                          # Daftar library yang dibutuhkan untuk menjalankan proyek
├── Grab_app_reviews.csv                                                      # Dataset ulasan
```
Penjelasan file:
- Kode_Scraping_Proyek_Analisis_Sentimen_Adelheid_Chantal_Lauw.ipynb:
  Notebook ini berisi kode untuk melakukan scraping data dari situs tertentu. Data yang dikumpulkan akan digunakan sebagai bahan untuk pelatihan     model.
- Notebook_Pelatihan_Proyek_Analisis_Sentimen_Adelheid_Chantal_Lauw.ipynb
  Berisi proses pembersihan data, eksplorasi data, dan pelatihan model machine learning.
- requirements.txt
  File ini berisi daftar dependensi Python yang dibutuhkan untuk menjalankan seluruh notebook. Dapat di-install dengan perintah:
  ```
  pip install -r requirements.txt
  ```
- Grab_app_reviews.csv
  Dataset hasil dari scraping data yang digunakan pada model pelatihan.

## Cara Menjalankan Proyek
1. Clone Repositori ini:
   ```
   git clone https://github.com/adelheidlauw/ProyekAnalisisSentimen.git
   cd ProyekAnalisisSentimen
   ```
2. Install semua dependensi:
   ```
   pip install -r requirements.txt
   ```
3. Jalankan notebook scraping:
   ```
   jupyter notebook Kode_Scraping_Proyek_Analisis_Sentimen_Adelheid_Chantal_Lauw.ipynb
   ```
4. Jalankan notebook pelatihan model:
   ```
   Notebook_Pelatihan_Proyek_Analisis_Sentimen_Adelheid_Chantal_Lauw.ipynb
   ```

## Hasil Akhir
Model analisis sentimen yang dilatih dapat mengklasifikasikan ulasan pengguna menjadi dua kategori, yaitu positif dan negatif.
