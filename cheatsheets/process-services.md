# Modul 6 — Process & Services

Modul ini membahas berbagai command Windows CMD yang digunakan untuk melihat, mengelola, menghentikan process, serta melakukan enumerasi service pada sistem Windows.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

* Melihat process yang sedang berjalan
* Menghentikan process berdasarkan nama atau PID
* Melakukan enumerasi service Windows
* Memahami management process dan service dasar

---

## Daftar Perintah

| Perintah                        | Fungsi                                |
| ------------------------------- | ------------------------------------- |
| `tasklist`                      | Menampilkan process aktif             |
| `tasklist /svc`                 | Menampilkan process beserta service   |
| `taskkill /PID <pid> /F`        | Menghentikan process berdasarkan PID  |
| `taskkill /IM <process.exe> /F` | Menghentikan process berdasarkan nama |
| `sc query`                      | Menampilkan service aktif             |
| `sc query state= all`           | Menampilkan seluruh service           |

---

## Catatan

* `tasklist` digunakan untuk melihat process yang sedang berjalan
* `taskkill` digunakan untuk menghentikan process Windows
* `sc query` berguna untuk enumerasi service pada sistem
* Service Windows sering digunakan dalam troubleshooting dan privilege escalation
* Beberapa command membutuhkan hak Administrator

---

## Navigasi

[← Kembali ke README Utama](../README.md)
