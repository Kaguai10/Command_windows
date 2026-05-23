# Modul 1 — System Information Windows

Modul ini membahas berbagai command Windows CMD yang digunakan untuk melihat informasi dasar sistem seperti user aktif, hostname, versi Windows, process, hardware, driver, dan update sistem.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

* Melihat informasi dasar sistem Windows
* Melakukan enumerasi sistem menggunakan CMD
* Mengetahui informasi hardware dan process
* Memahami command dasar untuk troubleshooting Windows

---

## Daftar Perintah

| Perintah                     | Fungsi                               |
| ---------------------------- | ------------------------------------ |
| `whoami`                     | Menampilkan user aktif               |
| `echo %username%`            | Menampilkan username                 |
| `hostname`                   | Menampilkan nama komputer            |
| `systeminfo`                 | Menampilkan informasi sistem lengkap |
| `ver`                        | Menampilkan versi Windows            |
| `wmic os get caption`        | Menampilkan nama OS                  |
| `set`                        | Menampilkan environment variables    |
| `date /t`                    | Menampilkan tanggal                  |
| `time /t`                    | Menampilkan waktu                    |
| `driverquery`                | Menampilkan daftar driver            |
| `tasklist`                   | Menampilkan process aktif            |
| `tasklist /svc`              | Menampilkan process dan service      |
| `wmic cpu get name`          | Menampilkan informasi processor      |
| `wmic bios get serialnumber` | Menampilkan serial BIOS              |
| `wmic qfe`                   | Menampilkan patch/update Windows     |

---

## Catatan

* `systeminfo` menampilkan informasi sistem secara lengkap
* `tasklist` berguna untuk melihat process yang sedang berjalan
* `driverquery` digunakan untuk melihat driver yang terinstall
* `wmic qfe` berguna untuk melihat update atau patch Windows
* Beberapa command memerlukan hak Administrator

---

## Navigasi

[← Kembali ke README Utama](../README.md)
