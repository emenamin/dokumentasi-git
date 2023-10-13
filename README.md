# dokumentasi-git

## Cara Menggunakan Git untuk Tracking Perubahan Versi
Disclaimer: Tutorial ini adalah hasil generate ChatGPT-4. Tutorial ini untuk kebutuhan pribadi dalam belajar menggunakan Git.

### 1. Inisialisasi Repository Lokal:

- Buka terminal atau command prompt.
- Pergi ke direktori tempat kode Anda disimpan.
- Ketik *git init* untuk menginisialisasi direktori sebagai repository Git.

### 2. Tambahkan File ke Staging Area:

Setelah melakukan perubahan pada file Anda, tambahkan mereka ke _staging area_ dengan menggunakan git add . (tanda titik di akhir untuk menambahkan semua file) atau git add <nama_file> untuk menambahkan file tertentu.

### 3. Commit Perubahan Anda:

Setelah Anda menambahkan file ke staging area, commit perubahan dengan git commit -m "Pesan commit Anda". Pesan commit harus menjelaskan perubahan apa yang Anda buat.
Melihat Riwayat Commit:

Anda bisa melihat riwayat commit dengan perintah git log. Ini akan menampilkan daftar semua commit yang telah Anda buat.

### 4. Melakukan Perubahan dan Menggunakan Branching:

Jika Anda ingin bekerja pada fitur atau perbaikan tertentu tanpa mengganggu kode utama, Anda bisa membuat branch baru dengan git branch <nama_branch> dan pindah ke branch tersebut dengan git checkout <nama_branch>.
Setelah Anda selesai dengan perubahan di branch tersebut, Anda bisa menggabungkannya kembali ke branch utama (biasanya master atau main) dengan menggunakan perintah git merge.
Memanfaatkan Tags:

Anda bisa menggunakan tags di Git untuk menandai versi tertentu dari kode Anda, misalnya untuk rilis. Gunakan git tag <nama_tag> untuk membuat tag baru.

### 5. Menyimpan Perubahan tanpa Commit:

Jika Anda memiliki perubahan yang belum siap untuk di-commit, tetapi Anda ingin menyimpannya untuk sementara, Anda bisa menggunakan git stash. Nanti, Anda dapat mengambil perubahan tersebut kembali dengan git stash apply.
