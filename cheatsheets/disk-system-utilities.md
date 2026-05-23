# Modul 8 — Disk & System Utilities

Modul ini membahas berbagai command Windows CMD yang digunakan untuk manajemen disk, pengecekan sistem, repair Windows, serta utility sistem lainnya.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

* Melakukan pengecekan dan repair sistem Windows
* Mengelola disk dan volume
* Memahami utility sistem dasar Windows
* Melakukan troubleshooting pada sistem Windows

---

## Daftar Perintah

| Perintah                                     | Fungsi                                     |
| -------------------------------------------- | ------------------------------------------ |
| `chkdsk`                                     | Mengecek kondisi disk                      |
| `diskpart`                                   | Manajemen disk dan partition               |
| `sfc /scannow`                               | Memperbaiki file sistem Windows            |
| `dism /online /cleanup-image /restorehealth` | Repair image Windows                       |
| `mountvol`                                   | Menampilkan volume dan mount point         |
| `fsutil fsinfo drives`                       | Menampilkan daftar drive                   |
| `fsutil file createnew`                      | Membuat file kosong dengan ukuran tertentu |
| `powercfg /a`                                | Menampilkan status power mode              |
| `wevtutil qe System`                         | Menampilkan log event system               |
| `eventvwr`                                   | Membuka Event Viewer                       |

---

## Catatan

* `sfc /scannow` sering digunakan saat Windows corrupt
* `dism` membantu repair image Windows yang rusak
* `diskpart` digunakan untuk manajemen disk dan partition
* `wevtutil` berguna untuk analisis log Windows
* Beberapa command membutuhkan hak Administrator

---

## Navigasi

[← Kembali ke README Utama](../README.md)
