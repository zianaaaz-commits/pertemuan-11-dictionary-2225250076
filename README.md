
# Pertemuan 11 - Dictionary/Map

Nama: Ziana Alfia Zahra  
NIM: 2225250076  
Kelas: 3A

## Tujuan

Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value.

## Struktur Data

Program menggunakan NIM sebagai key utama. Setiap value berupa dictionary yang berisi nama, kelas, dan nilai mahasiswa.

Program praktik menggunakan dua fungsi, yaitu `cari_mahasiswa()` untuk mencari data mahasiswa dan `rata_rata_nilai()` untuk menghitung rata-rata nilai mahasiswa.

## Cara Menjalankan

### Latihan

Jalankan setiap file latihan menggunakan perintah berikut:

```bash
python3 latihan/01_dasar_dictionary.py
python3 latihan/02_akses_get.py
python3 latihan/03_manipulasi_dictionary.py
python3 latihan/04_iterasi_dictionary.py
python3 latihan/05_dictionary_bersarang.py
python3 latihan/06_fungsi_dictionary.py
```

### Praktik

Jalankan program sistem data mahasiswa dengan perintah:

```bash
python3 praktik/data_mahasiswa.py
```

## Test Case

| Kasus | Input/Aksi | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| Pencarian tersedia | A003 | Data Citra ditampilkan | Data Citra ditampilkan | Berhasil |
| Pencarian tidak tersedia | A999 | Data tidak ditemukan | Data tidak ditemukan | Berhasil |
| Pembaruan nilai | A002 menjadi 82 | Nilai A002 berubah menjadi 82 | Nilai A002 berubah menjadi 82 | Berhasil |
| Penambahan data | A006 | Data mahasiswa A006 ditambahkan | Data mahasiswa A006 ditambahkan | Berhasil |
| Rekap data | Menggunakan `items()` | Semua NIM dan data mahasiswa ditampilkan | Semua NIM dan data mahasiswa ditampilkan | Berhasil |

## Refleksi

Saya mempelajari bahwa dictionary dapat menyimpan data menggunakan pasangan key dan value. Kesalahan dapat terjadi ketika mengakses key yang tidak tersedia. Untuk mengatasinya, saya menggunakan metode `get()` agar pencarian data dapat dilakukan dengan lebih aman.