
# Pertemuan 12 - File I/O dan Error Handling

Nama: Hikmah Azizah

NIM: 2225250086

Kelas: 3B

## Tujuan
Mempelajari cara membaca, menulis, memproses, dan memvalidasi file
menggunakan Python serta menangani error.

## Struktur Program
- data/: menyimpan file input dan output.
- latihan/: berisi enam latihan File I/O.
- tugas/: berisi program rekap nilai mahasiswa.

## Format File Input
Setiap baris menggunakan format NIM,nilai.

Contoh:
A001,85
A002,78
A003,92

## Cara Menjalankan
Jalankan dari root folder proyek:

python tugas/rekap_nilai_file.py

## Error yang Ditangani
- FileNotFoundError: file input tidak ditemukan.
- ValueError: format baris atau nilai tidak valid.
- Baris kosong dilewati.

## Test Case

| Kondisi | Hasil yang Diharapkan | Status |
|---|---|---|
| Semua nilai valid | Statistik dihitung | Berhasil |
| File tidak ditemukan | Pesan error ditampilkan | Berhasil |
| Nilai abc | Baris dilewati | Berhasil |
| Baris kosong | Baris dilewati | Berhasil |
| Nilai 60 | Dihitung lulus | Berhasil |

## Refleksi
Saya belajar menggunakan mode r, w, dan a untuk membaca,
menulis, serta menambahkan data ke file. Saya juga belajar
menangani FileNotFoundError dan ValueError agar program
tetap dapat memproses data valid meskipun ada baris yang salah.
