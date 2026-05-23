# Modul 3 — Network Enumeration

Modul ini membahas berbagai command Windows CMD yang digunakan untuk melihat konfigurasi jaringan, koneksi aktif, routing, DNS, port, dan informasi network lainnya pada sistem Windows.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

* Melihat konfigurasi jaringan Windows
* Mengecek koneksi dan port aktif
* Melakukan troubleshooting jaringan
* Memahami informasi routing dan DNS
* Melakukan enumerasi network dasar

---

## Daftar Perintah

| Perintah               | Fungsi                                        |
| ---------------------- | --------------------------------------------- |
| `ipconfig`             | Menampilkan konfigurasi IP dasar              |
| `ipconfig /all`        | Menampilkan konfigurasi jaringan lengkap      |
| `ipconfig /displaydns` | Menampilkan DNS cache                         |
| `ipconfig /flushdns`   | Menghapus DNS cache                           |
| `getmac`               | Menampilkan MAC address                       |
| `arp -a`               | Menampilkan ARP table                         |
| `route print`          | Menampilkan routing table                     |
| `netstat -an`          | Menampilkan koneksi dan port aktif            |
| `netstat -ano`         | Menampilkan koneksi beserta PID               |
| `netstat -b`           | Menampilkan aplikasi yang menggunakan koneksi |
| `ping <host>`          | Mengecek koneksi ke host                      |
| `tracert <host>`       | Menampilkan jalur routing ke host             |
| `pathping <host>`      | Analisis packet loss dan routing              |
| `nslookup <domain>`    | Melakukan DNS lookup                          |
| `net view`             | Menampilkan device/share dalam jaringan       |
| `net view \\target`    | Menampilkan share target                      |
| `nbtstat -n`           | Menampilkan NetBIOS lokal                     |
| `nbtstat -A <ip>`      | Menampilkan NetBIOS target                    |
| `net use`              | Menampilkan mapped network drive              |
| `net use \\ip\share`   | Mengakses network share                       |

---

## Catatan

* `ipconfig /all` sering digunakan untuk troubleshooting jaringan
* `netstat -ano` berguna untuk melihat port dan PID process
* `ping` dan `tracert` digunakan untuk pengecekan konektivitas
* `arp -a` digunakan untuk melihat device dalam jaringan lokal
* Beberapa command membutuhkan hak Administrator

---

## Navigasi

[← Kembali ke README Utama](../README.md)
