---
title: Akses SFTP menggunakan Command Line
date: '2021-07-24 22:48:15'
tags:
- sftp
- ssh
---

Sama-sama FTP, tapi ini pakai protokol SSH. SFTP ini bisa diakses melalui aplikasi FTP seperti Filezilla dll ataupun melalui console linux, powershell atau cmd.

Berikut ini merupakan perintah untuk akses SFTP menggunakan command line.

```bash
sftp user@192.168.11.1
```

Jika SSH pada server menggunakan custom port, maka tambahkan option `-P [PORT]`, sebagai contoh berikut:

```bash
sftp -P 2022 user@192.168.11.1
```

![SFTP](https://gh.iqbal.id/blog/img/sftp-test.png)

Untuk list perintah-perintah yang digunakan pada console sftp sama dengan ftp, silakan cek artikel berikut: [https://iqbal.id/blog/akses-ftp-menggunakan-command-line-di-linux](/blog/akses-ftp-menggunakan-command-line-di-linux)

Semoga bermanfaat.