# Modul 5 — Search & Forensics

Modul ini membahas berbagai command Windows CMD yang digunakan untuk pencarian file, analisis teks, hashing, enkripsi, dan kebutuhan digital forensik dasar pada sistem Windows.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

* Melakukan pencarian file dan teks
* Membandingkan isi file
* Membuat hash file
* Memahami command dasar digital forensik Windows
* Melakukan analisis file melalui CMD

---

## Daftar Perintah

| Perintah             | Fungsi                                             |
| -------------------- | -------------------------------------------------- |
| `find`               | Mencari teks pada file                             |
| `findstr`            | Mencari teks dengan filter lebih lanjut            |
| `findstr /s /i`      | Mencari teks secara recursive dan case-insensitive |
| `fc`                 | Membandingkan isi dua file                         |
| `certutil -hashfile` | Membuat hash file                                  |
| `cipher /c`          | Mengecek status enkripsi file                      |
| `cipher /w:c`        | Menghapus data kosong secara aman                  |
| `compact`            | Mengelola kompresi file NTFS                       |
| `forfiles`           | Menjalankan command berdasarkan filter file        |
| `dir /s`             | Mencari file dalam directory dan subdirectory      |

---

## Catatan

* `findstr` sering digunakan untuk mencari keyword penting pada banyak file
* `certutil -hashfile` berguna untuk verifikasi integritas file
* `fc` digunakan untuk membandingkan perbedaan antar file
* `cipher /w:c` membantu menghapus jejak data pada disk kosong
* Beberapa command membutuhkan hak Administrator

---

## Navigasi

[← Kembali ke README Utama](../README.md)
