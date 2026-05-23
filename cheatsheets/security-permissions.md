# Modul 7 — Security & Permissions

Modul ini membahas berbagai command Windows CMD yang digunakan untuk melihat dan mengelola permission, security policy, hak akses file, serta konfigurasi keamanan pada sistem Windows.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

* Melihat permission file dan folder
* Mengelola hak akses file
* Memahami security policy Windows
* Melakukan administrasi permission dasar
* Mengenal command keamanan Windows

---

## Daftar Perintah

| Perintah                      | Fungsi                             |
| ----------------------------- | ---------------------------------- |
| `icacls`                      | Menampilkan permission file/folder |
| `icacls <file> /grant user:F` | Memberikan hak akses full control  |
| `takeown /f <file>`           | Mengambil ownership file           |
| `auditpol`                    | Menampilkan audit policy           |
| `secedit`                     | Mengelola security policy          |
| `gpresult`                    | Menampilkan hasil Group Policy     |
| `gpupdate`                    | Memperbarui Group Policy           |
| `logoff`                      | Logout user saat ini               |
| `shutdown /s /t 0`            | Mematikan komputer                 |
| `shutdown /r /t 0`            | Restart komputer                   |

---

## Catatan

* `icacls` digunakan untuk melihat dan mengatur permission file
* `takeown` berguna saat akses file ditolak
* `gpresult` membantu melihat policy yang diterapkan pada user/system
* `auditpol` digunakan untuk melihat konfigurasi audit Windows
* Beberapa command membutuhkan hak Administrator

---

## Navigasi

[← Kembali ke README Utama](../README.md)
