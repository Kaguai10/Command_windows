# Modul 2 — User & Account Enumeration

Modul ini membahas berbagai command Windows CMD yang digunakan untuk melihat informasi user, group, privilege, session login, dan policy akun pada sistem Windows.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

* Melihat daftar user dan group pada Windows
* Melakukan enumerasi privilege user
* Mengecek policy akun dan password
* Mengetahui informasi session login user

---

## Daftar Perintah

| Perintah                         | Fungsi                                  |
| -------------------------------- | --------------------------------------- |
| `net user`                       | Menampilkan daftar user                 |
| `net user <username>`            | Menampilkan detail user                 |
| `net localgroup`                 | Menampilkan daftar local group          |
| `net localgroup administrators`  | Menampilkan anggota group administrator |
| `whoami /groups`                 | Menampilkan group user aktif            |
| `whoami /priv`                   | Menampilkan privilege user aktif        |
| `query user`                     | Menampilkan user yang sedang login      |
| `net accounts`                   | Menampilkan policy password             |
| `net user <username> /active:no` | Menonaktifkan user                      |
| `net user <username> *`          | Mengganti password user                 |

---

## Catatan

* `whoami /priv` sering digunakan saat privilege escalation
* `net user` berguna untuk enumerasi user pada Windows
* `query user` digunakan untuk melihat session login aktif
* Beberapa command membutuhkan hak Administrator

---

## Navigasi

[← Kembali ke README Utama](../README.md)
