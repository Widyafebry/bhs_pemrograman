# bahasa_pemrograman

## 1. pwd command
Perintah dasar Linux pwd berfungsi untuk mencari path dari direktori (folder) yang Anda gunakan saat ini. Perintah ini akan mengembalikan path yang absolut (penuh), yang pada dasarnya merupakan path semua direktori yang diawali dengan garis miring depan (/). Contoh dari path absolut adalah /home/username.

## 2. cd command
Untuk menjelajahi file dan direktori Linux, gunakan perintah cd. Perintah Linux ini memerlukan path penuh atau nama direktori, tergantung pada direktori yang Anda gunakan saat ini.

Misalkan saat ini Anda sedang berada di /home/username/Documents dan ingin membuka Photos, subdirektori dari Documents. Untuk melakukannya, Anda hanya perlu mengetikkan command ini: cd Photos.

Contoh lainnya, ketika Anda ingin beralih ke direktori yang sepenuhnya baru, misalnya, /home/username/Movies. Dalam contoh ini, ketik cd yang diikuti dengan path absolut direktori: cd /home/username/Movies.

Berikut beberapa jalan pintas (shortcut) untuk memudahkan navigasi:

cd .. (dengan dua tanda titik) untuk memindahkan satu direktori ke atas.
cd jika ingin langsung membuka folder home.
cd- (dengan tanda penghubung) untuk berpindah ke direktori sebelumnya.
Satu hal yang perlu diperhatikan, shell Linux sangat sensitif. Jadi, Anda harus mengetikkan nama direktori dengan benar dan tepat.

# 3. ls command
ls merupakan perintah dasar pada Linux yang digunakan untuk melihat konten atau isi direktori. Secara default, command ini akan menampilkan isi dari direktori yang Anda gunakan saat ini.

Jika ingin melihat isi direktori lain, ketik Is, disusul dengan path direktori. Contoh, ketik Is /home/username/Documents untuk melihat isi Documents.

Berikut beberapa variasi yang bisa dikombinasikan dengan perintah dasar Linux Is:

ls -R akan membuat daftar semua file yang ada di sub-direktori.
ls -aakan menampilkan file yang tersembunyi.
ls -alakan membuat daftar file dan direktori yang memuat informasi mendetail, seperti permission (hak akses), ukuran (size), pemilik (owner), dll.

## 4. cat command
cat (akronim dri concatenate) adalah salah satu perintah dasar sistem operasi Linux yang sering digunakan. Perintah ini berfungsi untuk membuat daftar konten atau isi file pada standard output (sdout). Untuk menjalankan command ini, ketik cat yang kemudian diikuti dengan nama dan ekstensi file. Sebagai contoh: cat file.txt.

Berikut beberapa cara untuk menggunakan perintah cat:

cat > filename untuk membuat file baru.
cat filename1 filename2>filename3untuk menggabungkan dua file (1 dan 2) dan menyimpan outputnya di file baru (3).
cat filename | tr a-z A-Z >output.txtuntuk mengonversi file ke penggunaan huruf besar atau huruf kecil.

## 5. cp command
Gunakan perintah dasar Linux cp untuk menyalin file dari direktori saat ini ke direktori yang berbeda. Misalnya, command cp scenery.jpg /home/username/Pictures untuk membuat salinan scenery.jpg (dari direktori saat ini) ke direktori Pictures.

## 6. mv command
Fungsi utama command mv adalah untuk memindahkan file meskipun sebenarnya bisa digunakan untuk mengganti atau mengubah nama file.
Argumen yang ada di mv serupa dengan argumen yang ada di perintah cp. Ketik mv, nama file, dan direktori tujuan. Contoh: mv file.txt /home/username/Documents.
Untuk mengganti nama file, perintah Linux-nya adalah mv oldname.ext newname.ext.

## 7. mkdir command
Untuk membuat direktori baru, Anda bisa menggunakan perintah dasar Linux mkdir. Sebagai contoh, jika Anda mengetik mkdir Music, direktori baru yang muncul disebut Music.

Berikut beberapa command mkdir tambahan:
Untuk membuat direktori baru di dalam direktori lain, gunakan command dasar Linux mkdir Music/Newfile.
Gunakan opsi p(parents) untuk membuat direktori di antara dua direktori yang sudah ada. Misalnya, mkdir -p Music/2020/Newfileuntuk membuat file baru “2020”.

## 8. rmdir command
Jika ingin menghapus direktori, gunakan perintah rmdir. Namun, rmdir hanya boleh digunakan untuk menghapus direktori kosong.

## 9. rm command
rm adalah perintah dasar pada Linux yang berfungsi untuk menghapus direktori beserta isinya. Jika hanya ingin menghapus direktorinya saja – alternatif command selain rmdir – gunakan rm -r.

Catatan: Saat menggunakan command ini, Anda harus berhati-hati dan cek kembali direktori di mana Anda berada saat ini. Sekali command rm dijalankan, maka semuanya akan terhapus dan tidak bisa dikembalikan.

## 10. touch command
touch adalah perintah dasar Linux yang memperbolehkan Anda membuat file baru yang kosong melalui baris perintah Linux. Sebagai contoh, ketik touch /home/username/Documents/Web.html untuk membuat file HTML berjudul Web di bawah direktori Documents.

## 11. history command
Kalau sudah lihai menggunakan Linux, Anda bisa menjalankan ratusan command atau perintah setiap hari. Misalnya, penggunaan command history untuk mengecek kembali (review) command yang sudah ditambahkan sebelumnya.
