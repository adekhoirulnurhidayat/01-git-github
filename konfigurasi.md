# Konfigurasi Git
Pengguna sebelum menggunakan harus memiliki Usename Serta Email agar semua perubahan dapat terhubung pada repo

1. masuk ke halaman github.com lalu daftarkan email,username, dan masukkan pasword
2. jika selesai tunggu verifikasi lewat email
3. jika sudah terverifiksi buka Github bash ketikan

```
$ git config --global user.name "Nama Anda di GitHub"
$ git config --global user.email email@domain.tld
```
4. untuk mengecek sudah berhasil silahkan ketikan
```
$ git config --list
```
jika user dan email muncul milik anda maka sudah berhasil 