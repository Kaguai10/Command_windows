# Modul 10 — Windows Privilege Escalation

Modul ini membahas berbagai command Windows CMD dan PowerShell yang sering digunakan untuk enumerasi privilege escalation, pengecekan konfigurasi sistem, service, permission, credential, dan informasi sensitif lainnya pada Windows.

---

## Tujuan Pembelajaran

Setelah mempelajari modul ini, diharapkan dapat:

* Melakukan enumerasi privilege escalation Windows
* Mengecek permission dan konfigurasi service
* Melihat privilege user dan policy sistem
* Mengidentifikasi potensi misconfiguration
* Memahami dasar reconnaissance Windows

---

## Daftar Perintah

| Perintah                                               | Fungsi                             |
| ------------------------------------------------------ | ---------------------------------- |
| `whoami /priv`                                         | Menampilkan privilege user         |
| `whoami /groups`                                       | Menampilkan group user             |
| `whoami /all`                                          | Menampilkan seluruh informasi user |
| `net user`                                             | Menampilkan daftar user            |
| `net localgroup administrators`                        | Menampilkan administrator          |
| `systeminfo`                                           | Menampilkan informasi sistem       |
| `hostname`                                             | Menampilkan hostname               |
| `tasklist /svc`                                        | Menampilkan process dan service    |
| `sc query`                                             | Menampilkan service aktif          |
| `sc qc <service>`                                      | Menampilkan konfigurasi service    |
| `wmic service get name,displayname,pathname,startmode` | Menampilkan konfigurasi service    |
| `icacls <file/folder>`                                 | Menampilkan permission file/folder |
| `accesschk.exe -uwcqv "Authenticated Users" *`         | Enumerasi service vulnerable       |
| `schtasks /query /fo LIST /v`                          | Menampilkan scheduled task         |
| `netstat -ano`                                         | Menampilkan koneksi dan PID        |
| `route print`                                          | Menampilkan routing table          |
| `arp -a`                                               | Menampilkan ARP table              |
| `ipconfig /all`                                        | Menampilkan konfigurasi jaringan   |
| `findstr /si password *.txt *.ini *.config`            | Mencari password pada file         |
| `reg query HKLM /f password /t REG_SZ /s`              | Mencari password pada registry     |
| `cmdkey /list`                                         | Menampilkan credential tersimpan   |
| `vaultcmd /list`                                       | Menampilkan Windows Vault          |
| `netsh wlan show profiles`                             | Menampilkan profile WiFi           |
| `netsh wlan show profile name="<wifi>" key=clear`      | Menampilkan password WiFi          |
| `wmic qfe`                                             | Menampilkan patch/update Windows   |
| `driverquery`                                          | Menampilkan daftar driver          |
| `set`                                                  | Menampilkan environment variables  |
| `echo %path%`                                          | Menampilkan PATH variable          |
| `powershell Get-ExecutionPolicy`                       | Menampilkan PowerShell policy      |
| `powershell Get-LocalUser`                             | Menampilkan local user             |
| `powershell Get-Service`                               | Menampilkan service Windows        |

---

## Catatan

* `whoami /priv` sangat penting dalam privilege escalation
* Enumerasi service sering digunakan untuk mencari misconfiguration
* `schtasks` membantu melihat task yang berjalan otomatis
* `findstr` dan `reg query` sering digunakan untuk mencari credential
* Beberapa tools seperti `accesschk.exe` berasal dari Sysinternals
* Beberapa command membutuhkan hak Administrator

---

## Navigasi

[← Kembali ke README Utama](../README.md)
