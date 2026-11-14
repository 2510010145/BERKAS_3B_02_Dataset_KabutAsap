# Dataset Anotasi Deteksi Objek Citra Berkabut dan Berasap

**Repository Tugas Kelompok 2 – Mata Kuliah Sistem Berkas**

## 1. Deskripsi Proyek

Repository ini berisi kumpulan dataset citra berkabut dan berasap yang telah dilengkapi dengan anotasi *bounding box* menggunakan format YOLO (`.txt`).

Proyek ini bertujuan untuk menyediakan dataset yang dapat digunakan dalam pengembangan dan pengujian sistem deteksi objek pada kondisi lingkungan berkabut atau berasap.

Pengerjaan dilakukan secara berkelompok dengan pembagian tugas kepada setiap anggota untuk mengumpulkan gambar, melakukan anotasi, serta mendokumentasikan kontribusi melalui GitHub.

## 2. Tujuan Proyek

1. Mengumpulkan citra yang menampilkan kondisi kabut atau asap.
2. Melakukan pelabelan objek menggunakan bounding box.
3. Menyediakan dataset dengan format anotasi YOLO.
4. Mendokumentasikan sumber setiap gambar yang digunakan.
5. Mengembangkan kerja sama dan kontribusi individu melalui GitHub.

## 3. Informasi Dataset

| Informasi | Keterangan |
|---|---|
| Mata Kuliah | Sistem Berkas |
| Kelompok | 02 |
| Tema | Dataset Citra Kabut Asap |
| Jenis Anotasi | Object Detection |
| Metode Anotasi | Bounding Box |
| Format Label | YOLO TXT |
| Tools | Roboflow |
| Target Minimum | 100 citra beranotasi |

## 4. Daftar Kelas Objek (Classes)

Kategori objek yang digunakan dalam dataset:

| ID Kelas | Nama Kelas | Keterangan |
|---|---|---|
| 0 | vehicle | Kendaraan |
| 1 | building | Gedung atau bangunan |
| 2 | person | Manusia |

Urutan ID kelas harus konsisten pada seluruh file anotasi YOLO dan konfigurasi dataset.

## 5. Struktur Direktori

```text
BERKAS_3B_02_Dataset_KabutAsap/
│
├── images/
│   └── Kumpulan gambar kabut dan asap
│
├── labels/
│   └── File anotasi YOLO (.txt)
│
├── sources.csv
│   └── Daftar sumber dan lisensi setiap gambar
│
├── classes.txt
│   └── Daftar nama kelas objek
│
├── README.md
├── .gitignore
└── LICENSE
```

## 6. Format Anotasi

Setiap gambar memiliki file anotasi YOLO dengan nama yang sama.

Contoh:

- `asap_001.jpg`
- `asap_001.txt`

Format anotasi YOLO terdiri dari ID kelas, koordinat tengah bounding box, lebar, dan tinggi yang telah dinormalisasi terhadap ukuran gambar.

## 7. Sumber Gambar

Setiap gambar yang digunakan dalam dataset wajib mencantumkan URL sumber aslinya.

Daftar sumber gambar disimpan dalam file `sources.csv` yang berada di direktori utama repository. Setiap gambar memiliki satu baris URL sumber yang sesuai dengan nama file gambar tersebut.

## 8. Tabel Kontribusi Kelompok 2

| Nama Anggota | NPM | Pembagian Tugas |
|---|---|---|
| Muhammad Nazmi Noor Abdhie (Ketua) | 2510010145 | Setup repository dan anotasi 20 citra |
| Muhammad Alvin Abrar | 2510010248 | Anotasi 20 citra |
| Muhammad Fajeri Ramadhan | 2510010492 | Anotasi 20 citra |
| Alfayet Romdoni | 2510010275 | Anotasi 20 citra |
| [Nama Anggota 5] | [NPM] | Anotasi 20 citra |

Bukti kontribusi setiap anggota berupa riwayat commit GitHub yang dilakukan menggunakan akun masing-masing.

Tautan commit setiap anggota akan dicantumkan setelah pengerjaan selesai.

## 9. Lisensi

Repository menggunakan MIT License untuk bagian proyek yang hak penggunaannya dimiliki oleh kelompok. Lisensi ini tidak otomatis mencakup hak cipta gambar yang berasal dari pihak lain.

Penggunaan setiap gambar tetap mengikuti lisensi dan ketentuan dari sumber aslinya.

## 10. Penutup

Melalui proyek ini, diharapkan kelompok dapat menghasilkan dataset citra berkabut dan berasap yang terstruktur, memiliki anotasi yang konsisten, serta dilengkapi dokumentasi sumber data dan bukti kontribusi setiap anggota.
