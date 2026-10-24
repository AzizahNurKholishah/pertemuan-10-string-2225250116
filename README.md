# Pertemuan 10 - String dan Pengolahan Teks

| Identitas | Keterangan |
|---|---|
| Nama | Azizah Nur Kholishah |
| NIM | 2225250116 |
| Kelas | 3-E |

## Tujuan

Memahami penggunaan string Python untuk membersihkan dan menormalisasi data teks, seperti nama mahasiswa dan kode kelas, agar formatnya lebih rapi dan konsisten.

## Cara Menjalankan

Program latihan dan tugas dapat dijalankan melalui terminal VS Code menggunakan perintah berikut:

- Latihan 1: `python3 latihan/01_string_dasar.py`
- Latihan 2: `python3 latihan/02_indeks_dan_slicing.py`
- Latihan 3: `python3 latihan/03_format_nama.py`
- Latihan 4: `python3 latihan/04_normalisasi_spasi.py`
- Latihan 5: `python3 latihan/05_split_join.py`
- Latihan 6: `python3 latihan/06_pencarian_teks.py`
- Tugas 4: `python3 tugas/normalisasi_data_mahasiswa.py`


## Algoritma

1. Mulai program.
2. Buat fungsi `normalisasi_nama()` untuk membersihkan spasi berlebih pada nama dan mengubah huruf awal setiap kata menjadi kapital.
3. Buat fungsi `buat_inisial()` untuk mengambil huruf pertama dari setiap kata pada nama.
4. Buat fungsi `normalisasi_kode()` untuk mengubah kode kelas menjadi huruf kapital dan mengganti pemisah antarkata menjadi tanda hubung.
5. Minta pengguna memasukkan nama mahasiswa dan kode kelas.
6. Normalisasi nama mahasiswa menggunakan fungsi `normalisasi_nama()`.
7. Normalisasi kode kelas menggunakan fungsi `normalisasi_kode()`.
8. Hitung jumlah kata pada nama yang sudah dinormalisasi.
9. Tentukan inisial nama menggunakan fungsi `buat_inisial()`.
10. Tampilkan nama bersih, kode kelas, jumlah kata, dan inisial nama.
11. Selesai.

## Test Case

| Input Nama | Input Kode Kelas | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| `aan hendrayana` | `pmat a 2026` | Aan Hendrayana, PMAT-A-2026, 2 kata, AH | Aan Hendrayana, PMAT-A-2026, 2 kata, AH | Berhasil |
| `fATHIYYAH mUTHMAINNAH` | `kelas b` | Fathiyyah Muthmainnah, KELAS-B, 2 kata, FM | Fathiyyah Muthmainnah, KELAS-B, 2 kata, FM | Berhasil |
| `BUDI` | `pmtk 01` | Budi, PMTK-01, 1 kata, B | Budi, PMTK-01, 1 kata, B | Berhasil |
| `siti nur aisyah` | `kelas c` | Siti Nur Aisyah, KELAS-C, 3 kata, SNA | Siti Nur Aisyah, KELAS-C, 3 kata, SNA | Berhasil |

## Refleksi

Masalah yang ditemukan saat mengolah teks adalah adanya spasi berlebih dan penggunaan huruf besar serta kecil yang tidak konsisten. Masalah tersebut dapat diperbaiki menggunakan `strip()`, `split()`, dan `join()` untuk membersihkan serta menyusun teks, kemudian `title()` dan `upper()` untuk menyeragamkan huruf. Dengan cara ini, data nama dan kode kelas menjadi lebih rapi dan mudah dibaca.

## Exit Ticket

- Operasi string yang paling berguna hari ini adalah strip() karena dapat menghilangkan spasi berlebih di awal dan akhir teks.
- Kesalahan pengolahan teks yang paling mungkin saya lakukan adalah lupa membersihkan spasi berlebih dan tidak menyeragamkan huruf besar dan kecil.
- Hubungan list dan string yang saya pahami adalah string dapat diubah menjadi list menggunakan split(), kemudian digabungkan kembali menjadi string menggunakan join().
- Konsep Pertemuan 10 yang akan membantu Pertemuan 11 adalah memahami pengolahan string, karena dapat membantu mengelola dan memproses data teks dalam program Python.

## Sumber dan Bantuan 

- Bahan Ajar Pertemuan 10 (Dr. Aan Hendrayana, S.Si., M.Pd.) sebagai acuan latihan, spesifikasi, dan test case.
- Python 3 Documentation: Text Sequence Type (`str`).
- Bantuan AI dipakai untuk menyusun kerangka kode dan draf README. Kode dan test case sudah saya jalankan serta pelajari, dan saya dapat menjelaskan alasan pemilihan operasi string pada setiap fungsi.