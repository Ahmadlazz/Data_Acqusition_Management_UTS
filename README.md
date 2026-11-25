# Data Acquisition Management - UTS

## Deskripsi
Proyek ini dibuat untuk memenuhi tugas UTS
mata kuliah Akuisisi dan Manajemen Data.

## Sumber Data
1. BPS Indonesia (CSV)
2. Day Bali Tour (Web Scraping)
3. OpenStreetMap Nominatim (API)

## Struktur Data
- data/raw/download: Data CSV BPS
- data/raw/scraping: Data HTML hasil scraping
- data/raw/api: Data hasil API
- data/process: Data hasil pengolahan
- docs: Dokumentasi dan metadata
- notebooks: Notebook pengerjaan

## Hasil Pengolahan
Data BPS dibersihkan dan digabung.
Data scraping dan API digabung menggunakan
Pandas merge dengan validasi many_to_one.

## Dokumentasi
Informasi sumber data, metadata merge,
dan checklist etika data tersedia di folder docs.
