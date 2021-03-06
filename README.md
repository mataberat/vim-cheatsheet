# vim-cheatsheet

### 1. Navigasi
Tombol `h` untuk geser ke kiri\
Tombol `j` untuk geser ke bawah\
Tombol `k` untuk geser ke atas, dan\
Tombol `l` untuk geser ke kanan.\

### 2. Navigasi lainnya
Tombol `e` untuk pindah ke karakter terakhir di sebuah kata jika berada di posisi lain di kata tersebut atau pindah ke karakter terakhir di kata berikutnya jika sudah berada di huruf terakhir sebuah kata.\
Tombol `w` untuk pindah ke karakter pertama kata selanjutnya.\
Tombol `b` untuk pindah ke karakter pertama di sebuah kata jika berada di posisi lain di kata berikut atau pindah ke karakter pertama sebuah kata.\
Tombol `^` untuk pindah ke karakter pertama (tidak termasuk spasi, tab, atau karakter kosong lain) di baris tertentu.\
Tombol `$` untuk pindah ke karakter terakhir di baris tertentu.\
Tombol `0` untuk pindah ke kolom pertama di baris tertentu.\
Tombol `{` untuk pindah ke awal paragraf saat ini.\
Tombol `}` untuk pindah ke akhir paragraf saat ini.\
Tombol `gg` (dua kali ditekan) untuk pindah ke baris paling atas.\
Tombol `G` untuk pindah ke baris paling bawah.\
Tombol `%` untuk pindah dari satu tanda kurng (`{}`, `()`, `()`) ke pasangannya.

### 3. Melakukan Navigasi Sekaligus Masuk ke Insert Mode
Tombol `a` dipakai untuk masuk ke insert mode di karakter setelah kursor (kebalikan dari tombol `i` yang masuk insert mode di karakter sebelum kursor).\
Tombol `I` dipakai untuk masuk ke insert mode di awal baris.\
Tombol `A` dipakai untuk masuk ke insert mode di akhir baris.\
Tombol `o` dipakai untuk masuk ke insert mode di bawah baris sekarang.\
Tombol `O` dipakai untuk masuk ke insert mode di atas baris sekarang.\
Tombol `r` dipakai untuk mengganti satu karakter dibelakang kursor dan masuk ke insert mode.

### 4. Mencari sebuah kata
1. `vim` `namafile.txt`
2. Tekan `/`
3. Masukan kalimat yang ingin dicari, dan
4. Tekan `Enter`.

### 5. Mencari Sebuah Kata Sekaligus Mengubah Kata
1. `vim` `namafile.txt`
2. Tekan `:%s/yang anda cari/kalimat yang menjadi perubahan/g`.

### 6. Menghapus
Tombol `D` untuk menghapus satu baris tanpa masuk ke insert mode.\
Tombol `C` untuk menghapus satu baris dan masuk ke insert mode.\
Tombol `dd` untuk cut satu baris dan `p` untuk paste satu baris yang di cut.

### 7. Block kalimat, copy, cut, dan paste
Tombol `v` untuk masuk ke visual selection/block mode.\
Tombol `V` untuk block satu baris.\
Tombol `y` untuk copy.\
Tombol `d` untuk cut.\
Tombol `p` untuk paste dibelakan cursor.\
Tombol `P` untuk paste didepan cursor

### 8. Undo dan Redo
Tombol `u` untuk undo.\
Tombol `Ctrl+R` untuk redo. 
