# Pertama kali memulai Projek

## Lakukan hal berikut &colon;

- cek apakah terinstal git

cek dengan :

`git --version` atau `git`

jika sudah terinstal, akan tercetak version git atau muncul banyak command git

- lakukan initiate config git :

`git config --global user.name "anak-ut"`

`git config --global user.email 031317495@ecampus.ut.ac.id`

*anak-ut* adalah username yang saya pakai

<031317495@ecampus.ut.ac.id> adalah email yang saya pakai.

Tanpa tanda kutip ya

- cek user dan email apakah sudah ok dengan cara :`git config --list`

Maka akan muncul keterangan username dan email yang kita config diatas
Untuk keluar dari terminal, tekan tombol \" q \" \( quit \)

- Selanjutnya cek folder  atau projek apakah sudah terdeteksi git

Ketik : `git status`
> muncul error karna belum ada direktori yang dikenali git

- Lakukan inisialisasi folder ke git dengan cara : `git init`

Maka git akan melacak direktori tsb.

Setelah itu, lakukan kembali `git status` untuk melihat bahwa file sudah terlacak oleh git

- Selanjutnya, tambahkan direktori ke staging area : `git add .`

Titik menandakan posisi direktori sekarang

cek kembali dengan : `git status`

maka akan muncul status bahwa file sudah ada di branch master, namun belum dicommit
File sekarang berada di staging area dan menunggu untuk kita commit.

- selanjutnya kita commit dengan cara : `git commit -m "Hello world dengan pedoman git pada projek"`

> "Hello world ..." adalah pesan pada commit yang harus diisi.

Penggunaan `git status` , `git add .` , dan `git commit -m "pesan"` akan sering digunakan.

Periksa *command git* : `git` untuk mengetahui perintah apa saja yang bisa digunakan.
