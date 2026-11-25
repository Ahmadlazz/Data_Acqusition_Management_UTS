
# Data Acquisition Management - UTS

## 1. Identitas Mahasiswa
- Nama: [Ahmad Paesoel]
- NIM: [2501010143]
- Kelas: F
- Program Studi: Informatika

## 2. Deskripsi Proyek
Proyek ini dibuat untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah Akuisisi dan Manajemen Data. Proyek ini mengangkat tema pariwisata di Bali dengan fokus pada pengelolaan informasi mengenai jumlah kunjungan wisatawan, destinasi wisata, dan paket perjalanan wisata. Data yang digunakan berasal dari beberapa sumber yang saling melengkapi, sehingga dapat memberikan gambaran yang lebih luas mengenai sektor pariwisata di Bali. Melalui proyek ini, informasi dari berbagai sumber dikumpulkan menjadi kumpulan data yang lebih terstruktur dan mudah dipahami.

## 3. Sumber Data
1. BPS Indonesia (dataset CSV)
2. Day Bali Tour (web scraping)
3. OpenStreetMap Nominatim (API)

## 4. Metode Akuisisi
- Mengunduh dataset CSV dari BPS.
- Melakukan web scraping menggunakan Python dan BeautifulSoup.
- Mengambil data lokasi menggunakan API Nominatim.

## 5. Tools yang Digunakan
- Python
- Google Colab
- Pandas
- Requests
- BeautifulSoup
- Git dan GitHub

## 6. Struktur Proyek
- data/raw/download/: Data CSV BPS.
- data/raw/scraping/: Data HTML hasil scraping.
- data/raw/api/: Data hasil API.
- data/process/: Data hasil pengolahan.
- docs/: Dokumentasi, provenance, metadata, dan checklist etika data.
- notebooks/: Notebook pengerjaan.

## 7. Hasil Pengolahan
Data BPS dibersihkan dan digabungkan.
Data paket wisata hasil scraping dan data lokasi dari API
digabungkan menggunakan Pandas merge dengan validasi many_to_one.

Hasil penggabungan diperiksa untuk memastikan tidak terdapat
duplikasi baris dan data lokasi yang hilang.

## 8. Dokumentasi
Informasi sumber data, metadata penggabungan, dan checklist etika data
tersedia di folder docs.

## 9. Catatan
Data mentah disimpan tanpa perubahan. Proses pembersihan dan pengolahan
dilakukan pada salinan data agar sumber aslinya tetap terjaga.
