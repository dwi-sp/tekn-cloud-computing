## Clone Repository

Proses clone adalah proses untuk menduplikasi remote repo di Github ke komputer lokal. Untuk melakukan proses clone menggunakan perintah berikut:

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-01/gambar/git-clone.jpg)

Setelah perintah ini, di direktori awesome-project akan disimpan isi repo yang sama dengan di GitHub. Perbedaannya, di komputer lokal terdapat direktori .git yang digunakan secara internal oleh Git.

## Mengelola Repo

### Mengubah Isi - Push Tanpa Branching dan Merging

Perubahan isi bisa terjadi karena satu atau kombinasi beberapa hal berikut:

1. File dihapus
2. File diedit
3. Membuat file / direktori baru
4. Menghapus direktori
   Untuk kasus-kasus tersebut, lakukan perubahan di komputer lokal, setelah itu push ke repo.

   ![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-01/gambar/git-batal-penambahan.jpg)

### Mengubah Isi dengan Branching and Merging

1. Buat branch untuk menampung perubahan-perubahan
2. Lakukan perubahan-perubahan
3. Add dan commit perubahan-perubahan tersebut ke branch
4. Kembali ke repo master
5. Buat pull request di GitHub
6. Merge pull request di GitHub
7. Merge branch untuk menampung perubahan-perubahan tersebut ke master.
8. Selesai.

Membuat pull request agar bisa di merger
![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-01/gambar/git-batal-penambahan.jpg)

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-01/gambar/git-branching-merger1.jpg)

setelah itu, Confirm Merge, branch yang kita kirimkan tadi sudah dimasukan ke branch master. Merge di komputer lokal:

### Sinkronisasi:

### Membatalkan Perubahan:

### Undo Commit Terakhir:

Contoh di atas adalah contoh untuk mengubah README.md dengan beberapa commit. Setelh itu, kita akan mengembalikan ke posisi terakhir sebelum commit terakhir.

Jika commit sudah dilakukan, tetapi belum di-push ke repo GitHub (masih berada di lokal), cara membatalkannya:

Untuk kembali ke perubahan pada saat yang sudah lama, yang perlu dilakukan adalah melakukan git revert kemudian mengedit secara manual kemudian push ke repo.

Edit file tersebut, setelah itu simpan.

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-01/gambar/git-revert2.jpg)

Setelah itu, lanjutkan proses revert. Saat git revert --continue isikan pesan revert.
![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-01/gambar/git-revert.jpg)
